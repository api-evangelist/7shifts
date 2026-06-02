# 7shifts (7shifts)

7shifts is a restaurant employee scheduling, time-tracking, and team management platform that helps restaurant operators forecast labor, build schedules, manage shift trades, run payroll integrations, and communicate with hourly staff. The platform integrates with major POS systems for sales data and labor forecasting and supports multi-location operations across quick-service, full-service, and franchise concepts. The 7shifts API v2 is a REST API authenticated via long-lived access tokens (Bearer) for internal use or OAuth 2.0 client credentials for technology partners, exposing employees, schedules, shifts, time punches, departments, locations, and wages.

**URL:** [Visit APIs.json URL](https://developers.7shifts.com/reference/introduction)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Scheduling, Workforce Management, Employee Scheduling, Time Tracking, HRIS, Labor

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-06-02

## APIs

### 7shifts REST API v2

REST API v2 for managing companies, locations, departments, roles, employees, schedules, shifts, time punches, wages, and time-off requests in 7shifts. Authentication uses Bearer access tokens for internal access or OAuth 2.0 client credentials for partner integrations.

**Human URL:** [https://developers.7shifts.com/reference/introduction](https://developers.7shifts.com/reference/introduction)

#### Tags:

 - Employees, Schedules, Shifts, Time Tracking, Locations, Wages, Time Off, Availability, Sales, Forecasting, Tasks, Tip Pool, Webhooks, Reporting

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/7shifts/refs/heads/main/openapi/7shifts-openapi.yml)
- [Documentation](https://developers.7shifts.com/reference/introduction)
- [Authentication](https://developers.7shifts.com/reference/authentication)
- [OAuth Authentication](https://developers.7shifts.com/docs/oauth-authentication)
- [GettingStarted](https://developers.7shifts.com/docs/getting-started)
- [Versioning](https://developers.7shifts.com/reference/versioning)
- [Postman](https://developers.7shifts.com/reference/postman-collection)
- [Webhooks](https://developers.7shifts.com/reference/webhooks-introduction)
- [RateLimits](https://developers.7shifts.com/reference/versioning)
- [Changelog](https://developers.7shifts.com/changelog)
- [Embed SDK](https://developers.7shifts.com/docs/embed-sdk-configuration)

## Common Properties

- [GitHubOrganization](https://github.com/7shifts)
- [LinkedIn](https://www.linkedin.com/company/7shifts)
- [Website](https://www.7shifts.com)
- [Documentation](https://developers.7shifts.com/)
- [APIReference](https://developers.7shifts.com/reference/introduction)
- [Pricing](https://www.7shifts.com/pricing)
- [SignUp](https://app.7shifts.com/signup)
- [Login](https://app.7shifts.com/login)
- [Support](https://support.7shifts.com/)
- [LLMsTxt](https://developers.7shifts.com/llms.txt)
- [Rules](rules/7shifts-spectral-rules.yml)
- [Vocabulary](vocabulary/7shifts-vocabulary.yml)
- [JSONLD](json-ld/7shifts-context.jsonld)
- [Plans](plans/7shifts-plans-pricing.yml)
- [RateLimits](rate-limits/7shifts-rate-limits.yml)
- [FinOps](finops/7shifts-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [7shifts API v2](openapi/7shifts-openapi.yml) — 21 paths, 33 operations, 16 schemas

### JSON Schema

- [Company](json-schema/7shifts-company-schema.json)
- [Location](json-schema/7shifts-location-schema.json)
- [Department](json-schema/7shifts-department-schema.json)
- [Role](json-schema/7shifts-role-schema.json)
- [User](json-schema/7shifts-user-schema.json)
- [Wage](json-schema/7shifts-wage-schema.json)
- [Shift](json-schema/7shifts-shift-schema.json)
- [Time Punch](json-schema/7shifts-timepunch-schema.json)
- [Time Off](json-schema/7shifts-timeoff-schema.json)
- [Availability](json-schema/7shifts-availability-schema.json)
- [Receipt](json-schema/7shifts-receipt-schema.json)
- [Webhook](json-schema/7shifts-webhook-schema.json)

### JSON Structure

- 12 JSON Structure documents under [json-structure/](json-structure/)

### JSON-LD

- [7shifts Context](json-ld/7shifts-context.jsonld)

### Examples

- 12 example payloads under [examples/](examples/)

## Capabilities

Naftiko capabilities, one self-contained file per API business surface (OpenAPI tag), each exposing a REST and an MCP adapter.

| Capability | APIs Combined | Tools | Persona |
|------------|--------------|-------|---------|
| [OAuth](capabilities/7shifts-oauth.yaml) | 7shifts | 1 | Partner Integrator |
| [Identity](capabilities/7shifts-identity.yaml) | 7shifts | 1 | Integrator |
| [Companies](capabilities/7shifts-companies.yaml) | 7shifts | 2 | Operator |
| [Locations](capabilities/7shifts-locations.yaml) | 7shifts | 3 | Operator |
| [Departments](capabilities/7shifts-departments.yaml) | 7shifts | 2 | Operator |
| [Roles](capabilities/7shifts-roles.yaml) | 7shifts | 2 | Operator |
| [Users](capabilities/7shifts-users.yaml) | 7shifts | 4 | HRIS Integrator |
| [Wages](capabilities/7shifts-wages.yaml) | 7shifts | 2 | Payroll Integrator |
| [Shifts](capabilities/7shifts-shifts.yaml) | 7shifts | 4 | Manager |
| [Time Punches](capabilities/7shifts-time-punches.yaml) | 7shifts | 3 | Manager |
| [Time Off](capabilities/7shifts-time-off.yaml) | 7shifts | 3 | Manager |
| [Availability](capabilities/7shifts-availability.yaml) | 7shifts | 1 | Manager |
| [Sales](capabilities/7shifts-sales.yaml) | 7shifts | 2 | POS Integrator |
| [Reporting](capabilities/7shifts-reporting.yaml) | 7shifts | 1 | Operator |
| [Webhooks](capabilities/7shifts-webhooks.yaml) | 7shifts | 2 | Integrator |

## Vocabulary

- [7shifts Vocabulary](vocabulary/7shifts-vocabulary.yml) — Unified taxonomy mapping 13 resources, 6 actions, 5 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [7shifts Spectral Ruleset](rules/7shifts-spectral-rules.yml) — 40+ rules across info, paths, operations, parameters, responses, schemas, security, and HTTP method categories enforcing 7shifts API conventions

## Plans & FinOps

- [Plans & Pricing](plans/7shifts-plans-pricing.yml) — Per-location subscription tiers (Comp, Entrée, The Works, Gourmet)
- [Rate Limits](rate-limits/7shifts-rate-limits.yml) — Per-access-token request throttling
- [FinOps](finops/7shifts-finops.yml) — FOCUS-aligned tiered-subscription billing model

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
