# S&P Global

S&P Global is a leading provider of credit ratings, benchmarks, analytics, and workflow solutions in the global capital, commodity, and automotive markets. Through its divisions — S&P Global Market Intelligence, S&P Global Ratings, S&P Global Commodity Insights, S&P Global Mobility, and S&P Dow Jones Indices — the company delivers data, analytics, and decisioning capabilities to financial institutions, corporations, governments, and individuals worldwide.

**Website:** [https://www.spglobal.com](https://www.spglobal.com)
**Developer Portal:** [https://developer.spglobal.com/](https://developer.spglobal.com/)
**Marketplace:** [https://www.marketplace.spglobal.com](https://www.marketplace.spglobal.com)
**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml)

## APIs

### S&P Global Commodity Insights API

HTTP-based RESTful API providing access to energy market data, commodity prices, assessments, and market intelligence across the Platts and S&P Global Commodity Insights business lines. Covers oil, gas, petrochemicals, power, shipping, metals, and agriculture. Uses Bearer token authentication.

- **Base URL:** `https://api.platts.com`
- **Documentation:** [https://developer.spglobal.com/commodityinsights/api/getting-started](https://developer.spglobal.com/commodityinsights/api/getting-started)
- **OpenAPI:** [openapi/s-and-p-global-commodity-insights-openapi.yml](openapi/s-and-p-global-commodity-insights-openapi.yml)
- **Python SDK:** [https://pypi.org/project/spgci/](https://pypi.org/project/spgci/)

### S&P Capital IQ Market Intelligence API

Comprehensive financial data API providing access to fundamental data, industry-specific and segment data, valuations and pricing, S&P Global Credit Ratings, and reference data.

- **Base URL:** `https://api-ciq.marketintelligence.spglobal.com`
- **Documentation:** [https://developer.marketintelligence.spglobal.com/catalog-service/](https://developer.marketintelligence.spglobal.com/catalog-service/)

### S&P Global Marketplace Catalog API

API providing programmatic access to the S&P Global Marketplace catalog of premium fundamental and alternative datasets.

- **Documentation:** [https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be)](https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be))

### Kensho Link API

S&P Global Kensho Link REST API for entity resolution and linking across financial instruments, companies, and other entities. Provides canonical entity identifiers (KEIDs) that link across all S&P Global data assets.

- **Base URL:** `https://api.link.kensho.com`
- **Documentation:** [https://api.link.kensho.com/docs/guides/rest-api/](https://api.link.kensho.com/docs/guides/rest-api/)
- **OpenAPI:** [openapi/s-and-p-global-kensho-link-openapi.yml](openapi/s-and-p-global-kensho-link-openapi.yml)

## OpenAPI Specifications

| API | File |
|-----|------|
| Commodity Insights API | [openapi/s-and-p-global-commodity-insights-openapi.yml](openapi/s-and-p-global-commodity-insights-openapi.yml) |
| Kensho Link API | [openapi/s-and-p-global-kensho-link-openapi.yml](openapi/s-and-p-global-kensho-link-openapi.yml) |

## Capabilities

Naftiko capabilities for S&P Global data workflows.

| Capability | Description |
|-----------|-------------|
| [capabilities/commodity-market-data.yaml](capabilities/commodity-market-data.yaml) | Commodity market data workflow for energy traders and analysts |
| [capabilities/financial-data-analytics.yaml](capabilities/financial-data-analytics.yaml) | Unified financial data analytics combining commodity pricing and entity resolution |

### Shared Definitions

| API | File |
|-----|------|
| Commodity Insights | [capabilities/shared/commodity-insights.yaml](capabilities/shared/commodity-insights.yaml) |
| Kensho Link | [capabilities/shared/kensho-link.yaml](capabilities/shared/kensho-link.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| Market Data Point | [json-schema/s-and-p-global-market-data-point-schema.json](json-schema/s-and-p-global-market-data-point-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| Market Data Point | [json-structure/s-and-p-global-market-data-structure.json](json-structure/s-and-p-global-market-data-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| S&P Global Context | [json-ld/s-and-p-global-context.jsonld](json-ld/s-and-p-global-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Current Market Data | [examples/s-and-p-global-get-current-market-data-example.json](examples/s-and-p-global-get-current-market-data-example.json) |
| Link Financial Entity | [examples/s-and-p-global-link-entity-example.json](examples/s-and-p-global-link-entity-example.json) |

## Rules

| Ruleset | File |
|---------|------|
| S&P Global Spectral Rules | [rules/s-and-p-global-spectral-rules.yml](rules/s-and-p-global-spectral-rules.yml) |

## Vocabulary

| Vocabulary | File |
|-----------|------|
| S&P Global Vocabulary | [vocabulary/s-and-p-global-vocabulary.yml](vocabulary/s-and-p-global-vocabulary.yml) |

## Tags

Financial Data, Credit Ratings, Market Intelligence, Commodity Insights, Energy Markets, Capital Markets, Fortune 500

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
