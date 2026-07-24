---
name: Save a customer and charge a stored card
description: Create a Helcim customer, read their stored cards, and charge one using the Payment API.
api: openapi/helcim-api.json
operations: [create-customer, get-customer-cards, purchase]
---

# Save a customer and charge a stored card

## Auth & setup
- `api-token` header with `Processing` permission; base URL `https://api.helcim.com/v2`.

## Steps
1. **`create-customer`** — `POST /customers`. Returns a `customerId` and `customerCode`.
2. **`get-customer-cards`** — `GET /customers/{customerId}/cards`. Fetch the customer's saved cards; pick the default (`set-customer-card-default` can change it).
3. **`purchase`** — `POST /payment/purchase` with the customer's `customerCode` and a required `idempotency-key` header to charge the stored card on file.

## Rules
- Storing cards reduces PCI scope; prefer tokenized cards over full card numbers.
- Idempotency-key (UUID 25-36 chars) is required on the purchase.
- Handle `{"errors": ...}` envelopes; a 403 means the token lacks the needed permission.
