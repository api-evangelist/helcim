---
name: Refund or reverse a Helcim payment
description: Reverse an unsettled authorization or refund a settled card transaction with the Helcim Payment API.
api: openapi/helcim-api.json
operations: [get-card-transaction, reverse, refund]
---

# Refund or reverse a payment

Choose the right operation based on settlement state.

## Auth & setup
- `api-token` header with `Processing` permission (refunds may require `Admin`); base URL `https://api.helcim.com/v2`.

## Steps
1. **`get-card-transaction`** — `GET /card-transactions/{cardTransactionId}`. Look up the original transaction and its batch/settlement state.
2. **If not yet settled → `reverse`** — `POST /payment/reverse`. Voids the authorization. Requires an `idempotency-key` header.
3. **If already settled → `refund`** — `POST /payment/refund`. Returns funds to the cardholder. Requires an `idempotency-key` header.

## Rules
- Reverse before settlement, refund after — reversing a settled transaction fails.
- Every reverse/refund needs a unique `idempotency-key` (UUID 25-36 chars); reuse only on retry.
- ACH equivalents: `ach-refund`, `ach-void`, `ach-cancel`.
