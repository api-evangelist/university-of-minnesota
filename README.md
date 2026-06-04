# University of Minnesota (university-of-minnesota)

The University of Minnesota is a public land-grant research university with its flagship campus in the Twin Cities (Minneapolis-Saint Paul), ranked #203 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an APIs.json profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-minnesota/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-minnesota-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Geospatial, United States, Minnesota

## APIs

- **Common Good APIs** — OIT Integrations Team suite over the Common Data Layer (person, HR, employee, student, class, organization, term data); access by request/approval. Docs: https://sites.google.com/umn.edu/integration-apis/common-good-apis
- **UMedia Digital Collection APIs** — UMN Libraries JSON + IIIF APIs for digital collection items, text, and metadata. Docs: https://github.com/UMNLibraries/digital_collection_apis
- **GEMS Informatics Exchange APIs** — Agricultural/geospatial data APIs (Climate, Weather, Soils, Hydro, Elevation, Land Cover, Crop Calendar, Market, Biotic Risk). Docs: https://gems.umn.edu/gems-exchange-apis

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/university-of-minnesota-plans-pricing.yml](plans/university-of-minnesota-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-minnesota-rate-limits.yml](rate-limits/university-of-minnesota-rate-limits.yml)
- FinOps: [finops/university-of-minnesota-finops.yml](finops/university-of-minnesota-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://twin-cities.umn.edu
- Developer Portal: https://sites.google.com/umn.edu/integration-apis/home
- GitHub: https://github.com/UMNLibraries
- Source Code: https://github.com/GEMS-UMN
- LinkedIn: https://www.linkedin.com/school/university-of-minnesota/
- Review: [review.yml](review.yml)

## Notes

All entries reflect publicly documented APIs verified live on 2026-06-03. The Common Good APIs are gated behind a request/approval workflow and institutional authentication; the documented Boomi base URL was not probed anonymously and no endpoints were fabricated. UMedia and the UDC/DRUM repository (Conservancy) are real public sites that return 403 to anonymous curl due to bot protection. The LinkedIn school page returns HTTP 999 (anti-bot) but exists. There is no single unified public API key portal across all UMN units; APIs are owned by distinct teams (OIT Integrations, Libraries, GEMS Informatics).

## Maintainers

- Kin Lane — kin@apievangelist.com
