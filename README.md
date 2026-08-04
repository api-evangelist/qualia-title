# Qualia (qualia-title)

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

Qualia is a digital real estate closing platform for the title, escrow, and settlement industry, connecting title agents, lenders, real estate agents, and homebuyers on a single system for managing closings end to end. The **Qualia API** is described publicly as an enterprise-grade, cloud-based **GraphQL** read-write API with a developer hub and sandbox. It lets real estate businesses and PropTech companies place and track title orders, send and receive messages and documents, and pull order, accounting, and contact data for custom reporting and to connect accounting, CRM, and BI systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qualia-title/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qualia-title/refs/heads/main/apis.yml)

## Access Model (Gated)

Qualia does **not** operate an open, unauthenticated developer portal. The public API pages ([qualia.com/qualia-api](https://www.qualia.com/qualia-api/) and [learn.qualia.com/api-u](https://learn.qualia.com/api-u)) are marketing and learning surfaces that direct developers to request a demo or call Qualia (855-441-5498). Access is provisioned **per organization** behind a secure authorization framework — capability gates, Authorized Organizations, HTTP authentication, and rate limiting — and governed by the [API Terms](https://www.qualia.com/api-terms/).

Because no public GraphQL endpoint URL, schema, or reference is published, the API areas below are **honestly modeled** from Qualia's public product and press material (`endpointsModeled`), not derived from a public schema. No concrete queries, mutations, or endpoint paths have been fabricated. There is no OpenAPI document (the API is GraphQL) and no documented public WebSocket API.

## Tags

- Title Insurance
- Escrow
- Real Estate
- Closing
- Settlement
- PropTech
- GraphQL

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs (Modeled)

### Qualia Title Orders API

Place title and escrow orders programmatically (into Qualia Core or to third-party systems) and track their status through the closing lifecycle.

- **Human URL:** [https://www.qualia.com/qualia-api/](https://www.qualia.com/qualia-api/)

### Qualia Documents API

Send and receive closing documents attached to an order — upload, retrieve, and share files across the parties on a file.

- **Human URL:** [https://www.qualia.com/qualia-api/](https://www.qualia.com/qualia-api/)

### Qualia Messages API

Send and receive messages tied to an order or transaction, powering client communication and status notifications alongside Qualia Connect.

- **Human URL:** [https://www.qualia.com/qualia-api/](https://www.qualia.com/qualia-api/)

### Qualia Contacts and Parties API

Pull contact and party data for the files on an account — the people and organizations attached to a closing — to sync with CRM systems and build custom notifications.

- **Human URL:** [https://www.qualia.com/qualia-api/](https://www.qualia.com/qualia-api/)

### Qualia Accounting and Escrow API

Pull accounting and escrow data across files for custom reporting and executive-level dashboards, and to connect Qualia to accounting platforms (e.g. NetSuite) and BI tools.

- **Human URL:** [https://www.qualia.com/qualia-api/](https://www.qualia.com/qualia-api/)


## Common Properties

- [LinkedIn](https://www.linkedin.com/company/qualiasoftware)
- [Website](https://www.qualia.com)
- [Documentation](https://www.qualia.com/qualia-api/)
- [Learning Resources](https://learn.qualia.com/api-u)
- [Terms of Service](https://www.qualia.com/api-terms/)
- [Plans](plans/qualia-title-plans-pricing.yml)
- [Rate Limits](rate-limits/qualia-title-rate-limits.yml)
- [Blog](https://blog.qualia.com/)

## Pricing

Qualia does not publish public, self-serve API pricing. The API is sold under a **capability-based, contact-sales** model — customers purchase the specific capabilities that meet their business objectives, provisioned per organization. See [plans/qualia-title-plans-pricing.yml](plans/qualia-title-plans-pricing.yml).

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
