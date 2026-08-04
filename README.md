# S&P Global (s-and-p-global)

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

S&P Global is a leading provider of credit ratings, benchmarks, analytics, and workflow solutions in the global capital, commodity, and automotive markets. Through its divisions — S&P Global Market Intelligence, S&P Global Ratings, S&P Global Commodity Insights, S&P Global Mobility, and S&P Dow Jones Indices — the company delivers data, analytics, and decisioning capabilities to financial institutions, corporations, governments, and individuals worldwide. S&P Global APIs enable programmatic access to financial data, market prices, energy market data, credit ratings, and geospatial intelligence.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Financial Data
- Credit Ratings
- Market Intelligence
- Commodity Insights
- Energy Markets
- Capital Markets
- Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### S&P Global Commodity Insights API

HTTP-based RESTful API providing access to energy market data, commodity prices, assessments, and market intelligence across the Platts and S&P Global Commodity Insights business lines. Supports market data, reference data, and historical prices for oil, gas, petrochemicals, power, shipping, and metals.

- **Human URL:** [https://developer.spglobal.com/commodityinsights/](https://developer.spglobal.com/commodityinsights/)
- **Base URL:** `https://api.platts.com`

#### Tags

- Commodity Insights
- Energy Markets
- Market Data
- Platts

#### Properties

- [Documentation](https://developer.spglobal.com/commodityinsights/api/getting-started)
- [OpenAPI](https://developer.spglobal.com/commodityinsights/servicecatalog) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.spglobal.com/commodityinsights/api/getting-started?tab=authentication)
- [S D Ks](https://pypi.org/project/spgci/)
- [Postman Collection](collections/s-and-p-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/s-and-p-global-kensho-link.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-kensho-link.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### S&P Capital IQ Market Intelligence API

Comprehensive financial data API providing access to fundamental data, industry-specific and segment data, valuations and pricing, S&P Global Credit Ratings and Research, and reference and terms and conditions data. Uses Bearer token authentication with tokens valid for 60 minutes.

- **Human URL:** [https://developer.marketintelligence.spglobal.com/](https://developer.marketintelligence.spglobal.com/)
- **Base URL:** `https://api-ciq.marketintelligence.spglobal.com`

#### Tags

- Market Intelligence
- Capital IQ
- Financial Data
- Credit Ratings

#### Properties

- [Documentation](https://developer.marketintelligence.spglobal.com/catalog-service/)
- [Authentication](https://developer.marketintelligence.spglobal.com/catalog-service/)
- [Postman Collection](collections/s-and-p-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/s-and-p-global-kensho-link.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-kensho-link.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### S&P Global Marketplace Catalog API

API providing programmatic access to the S&P Global Marketplace catalog of premium fundamental and alternative datasets. Enables discovery and integration of datasets available on the marketplace platform.

- **Human URL:** [https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d)](https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d))
- **Base URL:** `https://marketplace.spglobal.com`

#### Tags

- Marketplace
- Catalog
- Datasets

#### Properties

- [Documentation](https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be))
- [Postman Collection](collections/s-and-p-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/s-and-p-global-kensho-link.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-kensho-link.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kensho Link API

S&P Global Kensho Link REST API for entity resolution and linking across financial instruments, companies, and other entities. Provides a canonical entity identifier layer across S&P Global data assets.

- **Human URL:** [https://api.link.kensho.com/docs/guides/rest-api/](https://api.link.kensho.com/docs/guides/rest-api/)
- **Base URL:** `https://api.link.kensho.com`

#### Tags

- Kensho
- Entity Resolution
- Data Linking

#### Properties

- [Documentation](https://api.link.kensho.com/docs/guides/rest-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/openapi/s-and-p-global-kensho-link-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/s-and-p-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/s-and-p-global-kensho-link.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/s-and-p-global-kensho-link.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.spglobal.com)
- [Developer](https://developer.spglobal.com/)
- [Marketplace](https://www.marketplace.spglobal.com)
- [Documentation](https://developer.spglobal.com/commodityinsights/api/getting-started)
- [Authentication](https://developer.spglobal.com/commodityinsights/api/getting-started?tab=authentication)
- [Blog](https://www.spglobal.com/en/research-insights/articles)
- [LinkedIn](https://www.linkedin.com/company/spglobal/)
- [X (Twitter)](https://twitter.com/SPGlobal)
- [Pricing](https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be))
- [S D Ks](https://pypi.org/project/spgci/)
- [L L Ms Txt](https://developer.spglobal.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
