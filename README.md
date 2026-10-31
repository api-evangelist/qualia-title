# Qualia

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

Qualia is a digital real estate closing platform for the title, escrow, and settlement industry, connecting title agents, lenders, real estate agents, and homebuyers on a single system for managing closings end to end. The Qualia API is an enterprise-grade, cloud-based GraphQL read-write API with a developer hub and sandbox. It lets real estate businesses and PropTech companies place and track title orders, send and receive messages and documents, and pull order, accounting, and contact data for custom reporting and to connect accounting, CRM, and BI systems. Access is partner-gated behind a secure authorization framework (capability gates, authorized organizations, HTTP authentication, and rate limiting); Qualia does not publish an open, unauthenticated developer portal, so the API areas below are modeled from Qualia's public product and press material rather than from a public GraphQL schema.

**Areas:** Title Insurance · Escrow · Real Estate · Closing · Settlement · PropTech · GraphQL

## Qualia on APIs.io

Everything profiled for Qualia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/qualia-title/](https://apis.io/providers/qualia-title/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Qualia Title Orders API](https://apis.io/apis/qualia-title/qualia-title-orders-api/) — Place title and escrow orders programmatically (into Qualia Core or to third-party systems) and track their status through the closing lifecycle. Modeled…
- [Qualia Documents API](https://apis.io/apis/qualia-title/qualia-title-documents-api/) — Send and receive closing documents attached to an order - upload, retrieve, and share files across the parties on a file. Modeled from Qualia's stated…
- [Qualia Messages API](https://apis.io/apis/qualia-title/qualia-title-messages-api/) — Send and receive messages tied to an order or transaction, powering client communication and status notifications alongside Qualia Connect. Modeled from…
- [Qualia Contacts and Parties API](https://apis.io/apis/qualia-title/qualia-title-contacts-api/) — Pull contact and party data for the files on an account - the people and organizations attached to a closing - to sync with CRM systems and build custom…
- [Qualia Accounting and Escrow API](https://apis.io/apis/qualia-title/qualia-title-accounting-api/) — Pull accounting and escrow data across files for custom reporting and executive-level performance dashboards, and to connect Qualia to accounting platforms…
- [Qualia Connect and Marketplace API](https://apis.io/apis/qualia-title/qualia-title-marketplace-api/) — Programmatic access to Qualia's national network of technology-enabled independent title agents and Marketplace vendors, letting businesses without internal…
- [Qualia API](https://apis.io/apis/qualia-title/qualia-api/) — The Qualia API is a read-write GraphQL API over the Qualia title, escrow and closing platform. It lets partner organizations place title orders into Qualia…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Qualia Title Authentication](https://apis.io/security/qualia-title/qualia-title-authentication/)
- [Qualia Title Domain Security](https://apis.io/security/qualia-title/qualia-title-domain-security/)
- [Qualia Title Trust Center](https://apis.io/security/qualia-title/qualia-title-trust-center/)
- [Qualia Title Vulnerability Disclosure](https://apis.io/security/qualia-title/qualia-title-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Qualia Title Plans Pricing](https://apis.io/plans/qualia-title/qualia-title-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Qualia Title Rate Limits](https://apis.io/rate-limits/qualia-title/qualia-title-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.qualia.com)
- [Documentation](https://www.qualia.com/qualia-api/)
- [Pricing](https://www.qualia.com/qualia-api/)
- [Blog](https://blog.qualia.com/)
- [Security](https://www.qualia.com/.well-known/security.txt)
- [Compliance](https://www.qualia.com/trust/)
- [Terms of service](https://www.qualia.com/api-terms/)
- [Privacy policy](https://www.qualia.com/privacy-policy/)
- [GitHub](https://github.com/qualialabs)
- [Status](https://status.qualia.com/)

## API Evangelist rating

**Kin Score 34.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 57.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 68.4 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 27.2** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/qualia-title/](https://apis.io/providers/qualia-title/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Qualia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/qualia-title/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
