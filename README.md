# Northern Trust (northern-trust)

Northern Trust is a Fortune 500 global financial services firm providing asset servicing, asset management, wealth management, and banking to corporations, institutions, family offices, and individuals worldwide. Its first-party developer program, the Northern Trust API Store at [developer.ntrs.com](https://developer.ntrs.com/), exposes asset-servicing capabilities as REST APIs. Product domains are publicly browsable, but API reference specifications and live access sit behind Okta-based OIDC login.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/northern-trust/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** Partner (registration required — Okta OIDC)

## Tags

- Fortune 500
- Banking
- Wealth Management
- Asset Servicing
- Asset Management
- Financial Services
- United States

## APIs

The Northern Trust API Store publishes a family of asset-servicing APIs over the enterprise gateway (`https://apiservices.ntrs.com/ent/v1`), secured with Okta OIDC (OAuth2 authorization code + PKCE):

- **Custody API** — global custody holdings, positions, settlements, safekept assets
- **Fund Accounting API** — book of record accounting, valuations, NAV datasets
- **Transfer Agency API** — shareholder registers, subscriptions/redemptions, investor transactions
- **Middle Office API** — trade lifecycle, post-trade, reconciliation, investment operations
- **Data Management API** — consolidated investment/reference data, investment book of record
- **Risk and Performance API** — performance returns, attribution, benchmarks, risk analytics
- **Event Notification API** — asynchronous event/webhook notifications across servicing data

Product domains are publicly browsable; per-API reference specifications (downloadable in-portal as `spec.json`) and live access require registration and Okta login. No OpenAPI/Swagger is publicly downloadable without credentials, so none is harvested here. Northern Trust does not publish a public consumer open-banking / CFPB 1033 API; retail account connectivity is reached indirectly via data aggregators.

## Common Properties

- [Website](https://www.northerntrust.com)
- [Developer Portal](https://developer.ntrs.com/)
- [Documentation / API Catalog](https://developer.ntrs.com/apis)
- [Getting Started](https://developer.ntrs.com/get-started)
- [Support / Contact](https://developer.ntrs.com/contact-us)
- [Terms of Service](https://developer.ntrs.com/terms-and-conditions)
- [Privacy](https://developer.ntrs.com/global-privacy-standards)
- [Blog / Insights](https://www.northerntrust.com/united-states/insights-research)
- [GitHub Organization](https://github.com/northern-trust)
- [LinkedIn](https://www.linkedin.com/company/northern-trust)

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-07-23

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
