# Northern Trust (northern-trust)

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
