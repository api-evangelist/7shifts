# 7shifts

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

7shifts is a restaurant employee scheduling, time-tracking, and team management platform that helps restaurant operators forecast labor, build schedules, manage shift trades, run payroll integrations, and communicate with hourly staff. The platform integrates with major POS systems for sales data and labor forecasting and supports multi-location operations across quick-service, full-service, and franchise concepts. The 7shifts API v2 is a REST API authenticated via long-lived access tokens (Bearer) for internal use or OAuth 2.0 client credentials for technology partners, exposing employees, schedules, shifts, time punches, departments, locations, and wages.

**Areas:** Restaurant · Scheduling · Workforce Management · Employee Scheduling · Time Tracking · HRIS · Labor

## 7shifts on APIs.io

Everything profiled for 7shifts is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/7shifts/](https://apis.io/providers/7shifts/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [7shifts Availability API](https://apis.io/apis/7shifts/7shifts-availability-api/) — Employee availability records.
- [7shifts Companies API](https://apis.io/apis/7shifts/7shifts-companies-api/) — Company resources for 7shifts accounts.
- [7shifts Departments API](https://apis.io/apis/7shifts/7shifts-departments-api/) — Departments within a location.
- [7shifts Identity API](https://apis.io/apis/7shifts/7shifts-identity-api/) — Identity introspection for the authenticated token.
- [7shifts Locations API](https://apis.io/apis/7shifts/7shifts-locations-api/) — Physical restaurant locations within a company.
- [7shifts Reporting API](https://apis.io/apis/7shifts/7shifts-reporting-api/) — Sales, labor, and worked-hours reporting.
- [7shifts Roles API](https://apis.io/apis/7shifts/7shifts-roles-api/) — Job roles within a department.
- [7shifts Sales API](https://apis.io/apis/7shifts/7shifts-sales-api/) — Sales receipts and POS-integrated sales data.
- [7shifts Shifts API](https://apis.io/apis/7shifts/7shifts-shifts-api/) — Scheduled shifts assigned to users.
- [7shifts Time Off API](https://apis.io/apis/7shifts/7shifts-time-off-api/) — Time off requests and approvals.
- [7shifts Time Punches API](https://apis.io/apis/7shifts/7shifts-time-punches-api/) — Clock-in and clock-out time tracking records.
- [7shifts Users API](https://apis.io/apis/7shifts/7shifts-users-api/) — Users (employees) scoped to a company.
- [7shifts Wages API](https://apis.io/apis/7shifts/7shifts-wages-api/) — Hourly and salary wage records for users.
- [7shifts Webhooks API](https://apis.io/apis/7shifts/7shifts-webhooks-api/) — Company-level webhook subscriptions.
- [7shifts O Auth API](https://apis.io/apis/7shifts/7shifts-oauth-api/) — Token issuance for Partner OAuth applications.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [7Shifts Agentic Access](https://apis.io/agentic-access/7shifts/7shifts-agentic-access/)

#### JSON Schema (12)

The data models the API reads and writes.

- [Availability](https://apis.io/schemas/7shifts/7shifts-availability/)
- [Company](https://apis.io/schemas/7shifts/7shifts-company/)
- [Department](https://apis.io/schemas/7shifts/7shifts-department/)
- [Location](https://apis.io/schemas/7shifts/7shifts-location/)
- [Receipt](https://apis.io/schemas/7shifts/7shifts-receipt/)
- [Role](https://apis.io/schemas/7shifts/7shifts-role/)
- [Shift](https://apis.io/schemas/7shifts/7shifts-shift/)
- [Time Off](https://apis.io/schemas/7shifts/7shifts-timeoff/)
- [Time Punch](https://apis.io/schemas/7shifts/7shifts-timepunch/)
- [User](https://apis.io/schemas/7shifts/7shifts-user/)
- [Wage](https://apis.io/schemas/7shifts/7shifts-wage/)
- [Webhook](https://apis.io/schemas/7shifts/7shifts-webhook/)

#### JSON Structure (12)

Data models expressed in JSON Structure.

- [7Shifts Availability Structure](https://apis.io/json-structure/7shifts/7shifts-availability-structure/)
- [7Shifts Company Structure](https://apis.io/json-structure/7shifts/7shifts-company-structure/)
- [7Shifts Department Structure](https://apis.io/json-structure/7shifts/7shifts-department-structure/)
- [7Shifts Location Structure](https://apis.io/json-structure/7shifts/7shifts-location-structure/)
- [7Shifts Receipt Structure](https://apis.io/json-structure/7shifts/7shifts-receipt-structure/)
- [7Shifts Role Structure](https://apis.io/json-structure/7shifts/7shifts-role-structure/)
- [7Shifts Shift Structure](https://apis.io/json-structure/7shifts/7shifts-shift-structure/)
- [7Shifts Timeoff Structure](https://apis.io/json-structure/7shifts/7shifts-timeoff-structure/)
- [7Shifts Timepunch Structure](https://apis.io/json-structure/7shifts/7shifts-timepunch-structure/)
- [7Shifts User Structure](https://apis.io/json-structure/7shifts/7shifts-user-structure/)
- [7Shifts Wage Structure](https://apis.io/json-structure/7shifts/7shifts-wage-structure/)
- [7Shifts Webhook Structure](https://apis.io/json-structure/7shifts/7shifts-webhook-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [7Shifts Context](https://apis.io/jsonld/7shifts/7shifts-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [7Shifts Vocabulary](https://apis.io/vocabularies/7shifts/7shifts-vocabulary/)

#### Examples (12)

Example requests and responses.

- [7Shifts Availability Example](https://apis.io/examples/7shifts/7shifts-availability-example/)
- [7Shifts Company Example](https://apis.io/examples/7shifts/7shifts-company-example/)
- [7Shifts Department Example](https://apis.io/examples/7shifts/7shifts-department-example/)
- [7Shifts Location Example](https://apis.io/examples/7shifts/7shifts-location-example/)
- [7Shifts Receipt Example](https://apis.io/examples/7shifts/7shifts-receipt-example/)
- [7Shifts Role Example](https://apis.io/examples/7shifts/7shifts-role-example/)
- [7Shifts Shift Example](https://apis.io/examples/7shifts/7shifts-shift-example/)
- [7Shifts Timeoff Example](https://apis.io/examples/7shifts/7shifts-timeoff-example/)
- [7Shifts Timepunch Example](https://apis.io/examples/7shifts/7shifts-timepunch-example/)
- [7Shifts User Example](https://apis.io/examples/7shifts/7shifts-user-example/)
- [7Shifts Wage Example](https://apis.io/examples/7shifts/7shifts-wage-example/)
- [7Shifts Webhook Example](https://apis.io/examples/7shifts/7shifts-webhook-example/)

#### Collections (16)

Postman and Open Collection request collections.

- [7shifts API](https://apis.io/collections/7shifts/open-7shifts/)
- [7shifts Availability API](https://apis.io/collections/7shifts/open-7shifts-availability-api/)
- [7shifts Availability Companies API](https://apis.io/collections/7shifts/open-7shifts-companies-api/)
- [7shifts Availability Departments API](https://apis.io/collections/7shifts/open-7shifts-departments-api/)
- [7shifts Availability Identity API](https://apis.io/collections/7shifts/open-7shifts-identity-api/)
- [7shifts Availability Locations API](https://apis.io/collections/7shifts/open-7shifts-locations-api/)
- [7shifts Availability OAuth API](https://apis.io/collections/7shifts/open-7shifts-oauth-api/)
- [7shifts Availability Reporting API](https://apis.io/collections/7shifts/open-7shifts-reporting-api/)
- [7shifts Availability Roles API](https://apis.io/collections/7shifts/open-7shifts-roles-api/)
- [7shifts Availability Sales API](https://apis.io/collections/7shifts/open-7shifts-sales-api/)
- [7shifts Availability Shifts API](https://apis.io/collections/7shifts/open-7shifts-shifts-api/)
- [7shifts Availability Time Off API](https://apis.io/collections/7shifts/open-7shifts-time-off-api/)
- [7shifts Availability Time Punches API](https://apis.io/collections/7shifts/open-7shifts-time-punches-api/)
- [7shifts Availability Users API](https://apis.io/collections/7shifts/open-7shifts-users-api/)
- [7shifts Availability Wages API](https://apis.io/collections/7shifts/open-7shifts-wages-api/)
- [7shifts Availability Webhooks API](https://apis.io/collections/7shifts/open-7shifts-webhooks-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [7shifts — jsonschema rules](https://apis.io/rules/7shifts/7shifts-jsonschema-spectral-rules/)
- [7shifts API Rules](https://apis.io/rules/7shifts/7shifts-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [7Shifts Authentication](https://apis.io/security/7shifts/7shifts-authentication/)
- [7Shifts Domain Security](https://apis.io/security/7shifts/7shifts-domain-security/)
- [7Shifts Vulnerability Disclosure](https://apis.io/security/7shifts/7shifts-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [7Shifts Scopes](https://apis.io/scopes/7shifts/7shifts-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [7Shifts Plans Pricing](https://apis.io/plans/7shifts/7shifts-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [7Shifts Rate Limits](https://apis.io/rate-limits/7shifts/7shifts-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [7Shifts Finops](https://apis.io/finops/7shifts/7shifts-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.7shifts.com)
- [Documentation](https://developers.7shifts.com/)
- [API reference](https://developers.7shifts.com/reference/introduction)
- [Pricing](https://www.7shifts.com/pricing)
- [Support](https://support.7shifts.com/)
- [Blog](https://www.7shifts.com/blog/)
- [GitHub](https://github.com/7shifts)

## API Evangelist rating

**Kin Score 42.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 51.3 |
| Contract governance | 27.3 |
| Operational transparency | 38.2 |
| Developer ergonomics | 36.9 |
| Access clarity | 14.5 |

**Agent readiness 26.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 32.4** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/7shifts/](https://apis.io/providers/7shifts/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for 7shifts: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/7shifts/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
