# Qualia (qualia-title)

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

### Qualia Connect and Marketplace API

Programmatic access to Qualia's national network of technology-enabled independent title agents and Marketplace vendors, letting businesses without internal title operations place and route orders digitally.

- **Human URL:** [https://www.qualia.com/connect-for-title-and-escrow/](https://www.qualia.com/connect-for-title-and-escrow/)

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
