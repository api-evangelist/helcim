# Helcim

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Helcim is a Calgary, Canada based payment processor and merchant services provider serving small and medium-sized businesses across Canada and the United States with interchange-plus pricing and no monthly fees. Beyond its merchant dashboard, Smart Terminal hardware, and online store, Helcim ships a genuine developer surface: the versioned Helcim API (v2) for taking card and ACH payments, managing customers, cards, bank accounts and pre-authorized debits (PADs), issuing invoices, settling card and ACH batches, and driving in-person Card Terminal devices, alongside HelcimPay.js hosted checkout and connected-account webhooks. Authentication is a permissioned API access token passed in an api-token header, and the public developer portal publishes a downloadable OpenAPI 3.0 definition. In Canada's small, concentrated payments market, Helcim is one of the API-native SMB money-movement fintechs building above the incumbent acquiring and Interac rails.

**Areas:** Payments · Canada · Payment Gateway · Payment Processing · Acquiring · Merchant Services · ACH · Invoicing · Payment Terminals · Small Business

## Helcim on APIs.io

Everything profiled for Helcim is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/helcim/](https://apis.io/providers/helcim/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Helcim ACH Payment API](https://apis.io/apis/helcim/helcim-ach-payment-api/) — The ACH Payment API from Helcim — 8 operation(s) for ach payment.
- [Helcim Card Batch API](https://apis.io/apis/helcim/helcim-card-batch-api/) — The Card Batch API from Helcim — 3 operation(s) for card batch.
- [Helcim Card Terminal API](https://apis.io/apis/helcim/helcim-card-terminal-api/) — The Card Terminal API from Helcim — 1 operation(s) for card terminal.
- [Helcim Card Transaction API](https://apis.io/apis/helcim/helcim-card-transaction-api/) — The Card Transaction API from Helcim — 2 operation(s) for card transaction.
- [Helcim Customer API](https://apis.io/apis/helcim/helcim-customer-api/) — The Customer API from Helcim — 11 operation(s) for customer.
- [Helcim Device API](https://apis.io/apis/helcim/helcim-device-api/) — The Device API from Helcim — 5 operation(s) for device.
- [Helcim General API](https://apis.io/apis/helcim/helcim-general-api/) — The General API from Helcim — 1 operation(s) for general.
- [Helcim Invoice API](https://apis.io/apis/helcim/helcim-invoice-api/) — The Invoice API from Helcim — 2 operation(s) for invoice.
- [Helcim Payment API](https://apis.io/apis/helcim/helcim-payment-api/) — The Payment API from Helcim — 7 operation(s) for payment.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Helcim Webhooks](https://apis.io/asyncapis/helcim/helcim-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [helcim](https://apis.io/servers/helcim/helcim/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Helcim Agentic Access](https://apis.io/agentic-access/helcim/helcim-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [The Helcim API](https://apis.io/collections/helcim/open-helcim-api/)
- [The Helcim API](https://apis.io/collections/helcim/postman-helcim-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Helcim Api Overlay](https://apis.io/overlays/helcim/helcim-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Helcim Authentication](https://apis.io/security/helcim/helcim-authentication/)
- [Helcim Domain Security](https://apis.io/security/helcim/helcim-domain-security/)

#### Rate limits (1)

Published request limits.

- [Helcim Rate Limits](https://apis.io/rate-limits/helcim/helcim-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.helcim.com/)
- [Documentation](https://devdocs.helcim.com/docs)
- [Getting started](https://devdocs.helcim.com/docs/overview-of-helcim-api)
- [API reference](https://devdocs.helcim.com/reference)
- [Pricing](https://www.helcim.com/pricing/)
- [Sign up](https://hub.helcim.com/signup/register/)
- [Support](https://devdocs.helcim.com/docs/get-help)
- [Blog](https://www.helcim.com/blog/)
- [Compliance](https://devdocs.helcim.com/docs/pci-compliance-scope)
- [Terms of service](https://legal.helcim.com/ca/terms-of-service/)
- [Privacy policy](https://legal.helcim.com/ca/privacy-policy/)
- [GitHub](https://github.com/helcim)
- [Status](https://status.helcim.com)

## API Evangelist rating

**Kin Score 53.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 52.1 |
| Contract governance | 18.2 |
| Operational transparency | 77.6 |
| Developer ergonomics | 47.7 |
| Access clarity | 48.7 |

**Agent readiness 41.3** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 31.7** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/helcim/](https://apis.io/providers/helcim/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Helcim: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/helcim/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
