---
name: Take a card payment with Helcim
description: Charge a card end-to-end with the Helcim API v2 — verify connectivity, then run a Purchase with a required idempotency key.
api: openapi/helcim-api.json
operations: [connectionTest, purchase]
---

# Take a card payment

Use the Helcim Payment API to process a one-time card purchase.

## Auth & setup
- Send your API access token in the `api-token` header on every request. The token must have `Processing` permission.
- Base URL: `https://api.helcim.com/v2` (test: `https://api.helcim.test/v2`).

## Steps
1. **`connectionTest`** — `GET /connection-test`. Confirms the token is valid before charging (200 = `{"message":"Connection Successful"}`).
2. **`purchase`** — `POST /payment/purchase`. Send an `idempotency-key` header (UUID, 25-36 chars) — it is **required** and protects against duplicate charges (reusing the key returns the original result). Body includes `currency`, `amount`, and either `cardData` (full card / token) or a stored `customerCode`.

## Rules
- Idempotency key is mandatory on every write payment op — generate a fresh UUID per logical charge, reuse it only on retries.
- Rate limits: 5 concurrent / 100 per minute / 3000 per hour; back off on HTTP 429.
- In test accounts, a `cardCVV` of 200+ forces a decline (see errors/helcim-decline-codes.yml).
- On failure the response is `{"errors": "<message>"}` — do not retry non-idempotently on ambiguous errors; re-send with the same idempotency-key.
