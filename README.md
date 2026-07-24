# Helcim (helcim)

Helcim is a Calgary, Canada based payment processor and merchant services provider serving small and medium-sized businesses across Canada and the United States with interchange-plus pricing and no monthly fees. Alongside its merchant dashboard, Smart Terminal hardware, and online store, Helcim ships a genuine developer surface — the versioned Helcim API (v2) for card and ACH payments, customers, invoices, batches, and in-person terminals — plus HelcimPay.js hosted checkout and connected-account webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/helcim/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/helcim/refs/heads/main/apis.yml)

## Tags

- Payments
- Canada
- Payment Gateway
- Payment Processing
- Acquiring
- Merchant Services
- ACH
- Invoicing
- Card Terminal
- Small Business

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## API Posture

- **Developer portal:** [https://devdocs.helcim.com](https://devdocs.helcim.com) (ReadMe.io, HTTP 200)
- **API reference:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **OpenAPI:** one real OpenAPI 3.0.0 definition — "The Helcim API" v2.2.0, 40 paths — harvested verbatim to [`openapi/helcim-api.json`](openapi/helcim-api.json)
- **Authentication:** API key in an `api-token` header (permissioned API Access Configuration)
- **Events:** connected-account webhooks
- **Home market:** Canada (with US coverage)

## APIs

### Helcim Payment API

Card payment processing across the full transaction lifecycle — Purchase, Preauthorization, Capture, Verify, Refund, Reverse, and Withdraw — plus a connection-test endpoint.

- **Human URL:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **Properties:** [OpenAPI](openapi/helcim-api.json) · [Documentation](https://devdocs.helcim.com/docs/overview-of-helcim-api)

### Helcim ACH Payment API

Bank-to-bank (ACH / pre-authorized debit) money movement — withdraw, refund, void, cancel, retrieve ACH transactions, and list and settle ACH batches.

- **Human URL:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **Properties:** [OpenAPI](openapi/helcim-api.json) · [Documentation](https://devdocs.helcim.com/docs/overview-of-helcim-api)

### Helcim Customer API

Create, retrieve, and update customers and manage their saved payment instruments — stored cards, bank accounts, and pre-authorized debit agreements (PADs).

- **Human URL:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **Properties:** [OpenAPI](openapi/helcim-api.json) · [Documentation](https://devdocs.helcim.com/docs/overview-of-helcim-api)

### Helcim Invoice API

Create, retrieve, and update invoices for billing and payment collection.

- **Human URL:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **Properties:** [OpenAPI](openapi/helcim-api.json) · [Documentation](https://devdocs.helcim.com/docs/overview-of-helcim-api)

### Helcim Card Transaction & Batch API

Read access to processed card transactions and card batches, including settling a card batch.

- **Human URL:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **Properties:** [OpenAPI](openapi/helcim-api.json) · [Documentation](https://devdocs.helcim.com/docs/overview-of-helcim-api)

### Helcim Card Terminal & Device API

In-person payments through Helcim Smart Terminal hardware — list terminals and devices, ping a device, and start purchase or refund transactions.

- **Human URL:** [https://devdocs.helcim.com/reference](https://devdocs.helcim.com/reference)
- **Base URL:** `https://api.helcim.com/v2`
- **Properties:** [OpenAPI](openapi/helcim-api.json) · [Documentation](https://devdocs.helcim.com/docs/overview-of-helcim-api)

## Common Properties

- [Website](https://www.helcim.com/)
- [Developer Portal](https://devdocs.helcim.com/)
- [Documentation](https://devdocs.helcim.com/docs)
- [API Reference](https://devdocs.helcim.com/reference)
- [Getting Started](https://devdocs.helcim.com/docs/overview-of-helcim-api)
- [Authentication](https://devdocs.helcim.com/docs/authentication-with-the-helcim-api-and-helcimpayjs)
- [Webhooks](https://devdocs.helcim.com/docs/connected-account-webhooks)
- [GitHub Organization](https://github.com/helcim)
- [Status Page](https://status.helcim.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
