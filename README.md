# Altruistiq (altruistiq)

Altruistiq is a London-based climate intelligence platform for food and beverage and other FMCG enterprises managing complex supply chains. The platform unifies corporate carbon footprint reporting, product carbon footprint (PCF) calculation, and supplier engagement on a single ISO 14064-1 assured calculation engine, drawing raw operational data from finance, procurement, and supply chain systems to produce activity-based Scope 1, 2, and 3 emissions measurements. Altruistiq exposes a public Datasource API and a PACT-conformant Product Carbon Footprint data exchange API (OAuth 2.0 client credentials) for uploading activity data, managing products, bills of materials, facilities, and exporting calculated emissions. Customers include Starbucks, Kraft Heinz, Huel, Nando's, Octopus Energy, and other FMCG and food and beverage brands.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/altruistiq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/altruistiq/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Sustainability
- Climate
- Carbon Accounting
- Emissions
- Greenhouse Gas
- Scope 3
- Product Carbon Footprint
- Corporate Carbon Footprint
- Supply Chain
- FMCG
- Food and Beverage
- ESG
- CSRD
- SBTi
- PACT
- Sustainability Intelligence

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Altruistiq Datasource API

Upload, manage, and export activity and product data used to calculate enterprise emissions on the Altruistiq platform. Covers multipart file uploads into named Datasources, corporate emissions Exports with filtering and download URLs, full CRUD on Products, Product Structures (bills of materials), and Product Structure Inputs (material and packaging line items), Facility version management, geographic Location reference data (countries and subdivisions), and Organization and business unit lookups. Authenticated via OAuth 2.0 Client Credentials against /api/public/v1/oauth2/token. Production server is https://app.altruistiq.com/api/public/v1.

- **Human URL:** [https://docs.altruistiq.com](https://docs.altruistiq.com)
- **Base URL:** `https://app.altruistiq.com/api/public/v1`

#### Tags

- Sustainability
- Carbon Accounting
- Emissions
- Datasource
- Products
- Facilities
- Export

#### Properties

- [Documentation](https://docs.altruistiq.com)
- [OpenAPI](openapi/altruistiq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/altruistiq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/altruistiq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.altruistiq.com)
- [JSON Schema](json-schema/altruistiq-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/altruistiq-facility-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/altruistiq-emission-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/altruistiq-product-structure.json)
- [JSON-LD](json-ld/altruistiq-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Ruleset](rules/altruistiq-rules.yml)
- [Vocabulary](vocabulary/altruistiq-vocabulary.yml)
- [Example](examples/altruistiq-oauth-token-example.json)
- [Example](examples/altruistiq-create-product-example.json)
- [Example](examples/altruistiq-create-export-example.json)
- [Example](examples/altruistiq-get-export-example.json)

### Altruistiq PACT API

PACT-conformant Product Carbon Footprint data exchange surface for sharing ingredient-level PCF data with customers and partners per the WBCSD Partnership for Carbon Transparency (PACT) Pathfinder Framework. Exposed through the same /api/public/v1 surface alongside the Datasource API. Used to fulfil B2B customer RFPs and downstream Scope 3 reporting requests with traceable, methodology-aware PCFs.

- **Human URL:** [https://docs.altruistiq.com](https://docs.altruistiq.com)
- **Base URL:** `https://app.altruistiq.com/api/public/v1`

#### Tags

- Sustainability
- Carbon Accounting
- Product Carbon Footprint
- PACT
- Pathfinder
- Interoperability

#### Properties

- [Documentation](https://docs.altruistiq.com)
- [OpenAPI](openapi/altruistiq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/altruistiq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/altruistiq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Standard](https://www.carbon-transparency.org)
- [JSON-LD](json-ld/altruistiq-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Website](https://www.altruistiq.com)
- [Portal](https://www.altruistiq.com/platform/overview)
- [Documentation](https://docs.altruistiq.com)
- [Platform](https://app.altruistiq.com)
- [Sign Up](https://www.altruistiq.com/get-in-touch)
- [Company](https://www.altruistiq.com/company)
- [Careers](https://www.altruistiq.com/careers)
- [Blog](https://www.altruistiq.com/insights)
- [Customers](https://www.altruistiq.com/customers)
- [Capabilities](https://www.altruistiq.com/data-capabilities)
- [Solution](https://www.altruistiq.com/solutions/corporate-carbon-footprint)
- [Solution](https://www.altruistiq.com/solutions/product-carbon-footprint)
- [Solution](https://www.altruistiq.com/solutions/supply-chain-decarbonisation)
- [Solution](https://www.altruistiq.com/evie)
- [Security](https://www.altruistiq.com/security)
- [Trust Center](https://www.altruistiq.com/security)
- [Privacy Policy](https://www.altruistiq.com/privacy-policy)
- [Terms of Service](https://www.altruistiq.com/terms-of-service)
- [LinkedIn](https://www.linkedin.com/company/altruistiq)
- [Twitter](https://twitter.com/altruistiq)
- [GitHub Organization](https://github.com/altruistiq)
- [Standard](https://www.carbon-transparency.org)
- [Standard](https://www.iso.org/standard/66453.html)
- [Standard](https://ghgprotocol.org)
- [Standard](https://sciencebasedtargets.org)
- [Standard](https://finance.ec.europa.eu/capital-markets-union-and-financial-markets/company-reporting-and-auditing/company-reporting/corporate-sustainability-reporting_en)
- [Plans](plans/altruistiq-plans-pricing.yml)
- [Rate Limits](rate-limits/altruistiq-rate-limits.yml)
- [Fin Ops](finops/altruistiq-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
