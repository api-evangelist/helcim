# Helcim (helcim)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
