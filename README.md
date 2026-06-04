# Monash University (monash)

Monash University is a public research university in Melbourne, Australia, and a member of the Group of Eight, ranked #42 in the QS World University Rankings 2025. This repository catalogs Monash's public, machine-readable developer and API footprint as an [APIs.json](https://apisjson.org) profile. That footprint is modest and largely indirect — research data is published via monash.figshare on the figshare platform, and Monash eResearch operates the CRAMS API portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/monash/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=monash-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Australia

## APIs

- **Monash University Research Repository (monash.figshare)** — Monash research data repository on the figshare platform, accessible via the figshare v2 REST API and OAI-PMH for metadata harvesting.
  - Docs: https://docs.figshare.com/
  - Repository: https://monash.figshare.com/
  - OAI-PMH: https://api.figshare.com/v2/oai
- **CRAMS API (Cloud Resource Allocation and Management System)** — Monash eResearch API portal for managing research cloud resource allocations (institutional/gated access).
  - Portal: https://crams-api.erc.monash.edu/

## Plans

- [plans/monash-plans-pricing.yml](plans/monash-plans-pricing.yml)

## Rate Limits

- [rate-limits/monash-rate-limits.yml](rate-limits/monash-rate-limits.yml)

## FinOps

- [finops/monash-finops.yml](finops/monash-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.monash.edu/
- Research: https://research.monash.edu/
- GitHub: https://github.com/monash-university
- Source Code: https://github.com/MonashStudentInnovation
- LinkedIn: https://www.linkedin.com/school/monash-university/

## Notes

All cataloged URLs were probed during research. The official `monash-university` GitHub org exists but currently has no public repositories. `monash.figshare` runs on the figshare platform, so its programmatic access is provided by the shared figshare v2 API and OAI-PMH endpoint rather than a Monash-hosted API. The CRAMS portal landing page resolves but its API is institutional/gated with no open specification located. No central, openly documented institutional developer portal for course/catalog/timetable/SIS APIs was found. The `TheBetterHandbookAPI` project is community-built and not an official Monash service. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
