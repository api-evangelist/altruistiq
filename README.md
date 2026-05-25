# altruistiq

Altruistiq is a London-based climate intelligence platform for food and beverage and other FMCG enterprises managing complex supply chains. The platform unifies corporate carbon footprint reporting, product carbon footprint (PCF) calculation, and supplier engagement on a single ISO 14064-1 assured calculation engine, drawing raw operational data from finance, procurement, and supply chain systems to produce activity-based Scope 1, 2, and 3 emissions measurements.

Customers include Starbucks, Kraft Heinz, Huel, Nando's, Octopus Energy, and other FMCG and food and beverage brands.

## APIs

- **[Altruistiq Datasource API](openapi/altruistiq-openapi.yml)** — Upload activity data via multipart uploads into named Datasources; manage Products, Product Structures (BOMs), and Product Structure Inputs; manage versioned Facilities; look up geographic Location reference data and Organization business units; export filtered corporate emissions with download URLs. OAuth 2.0 Client Credentials.
- **Altruistiq PACT API** — PACT Pathfinder-conformant Product Carbon Footprint data exchange surface, served alongside the Datasource API.

## Artifacts

- [openapi/altruistiq-openapi.yml](openapi/altruistiq-openapi.yml) — Public OpenAPI 3 specification (25 paths across nine resource groups).
- [json-schema/](json-schema/) — JSON Schemas for Product, Facility, and Emission Record.
- [json-structure/altruistiq-product-structure.json](json-structure/altruistiq-product-structure.json) — Product Structure / Inputs documentation.
- [json-ld/altruistiq-context.jsonld](json-ld/altruistiq-context.jsonld) — JSON-LD context aligning Altruistiq entities with schema.org, GHG Protocol, and PACT vocabularies.
- [examples/](examples/) — OAuth token, Create Product, Create Export, and Get Export examples.
- [rules/altruistiq-rules.yml](rules/altruistiq-rules.yml) — Spectral ruleset reflecting Altruistiq API conventions.
- [vocabulary/altruistiq-vocabulary.yml](vocabulary/altruistiq-vocabulary.yml) — Domain vocabulary across carbon accounting, the Altruistiq platform, interoperability, reporting standards, and API mechanics.
- [capabilities/](capabilities/) — Naftiko capability definitions: `oauth`, `datasource`, `export`, `products`, `product-structures`, `product-structure-inputs`, `facilities`, `location`, `organization`.
- [plans/altruistiq-plans-pricing.yml](plans/altruistiq-plans-pricing.yml) — Plan structure (sales-led; Contact Sales pricing).
- [rate-limits/altruistiq-rate-limits.yml](rate-limits/altruistiq-rate-limits.yml) — Rate-limit policy (per-tenant fair-use; not publicly enumerated).
- [finops/altruistiq-finops.yml](finops/altruistiq-finops.yml) — FOCUS-aligned FinOps definition for the enterprise subscription.

## Links

- Website: https://www.altruistiq.com
- Documentation: https://docs.altruistiq.com
- Platform: https://app.altruistiq.com
- GitHub: https://github.com/altruistiq
- Standards: GHG Protocol, ISO 14064-1, PACT Pathfinder, SBTi, CSRD
