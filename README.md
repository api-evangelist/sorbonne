# Sorbonne University (sorbonne)

Sorbonne University (Sorbonne Université) is a public research university in Paris, France, formed in 2018 from the merger of Paris-Sorbonne and Pierre et Marie Curie universities. It serves roughly 53,000 students and is ranked #81 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/sorbonne/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sorbonne-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Science, Research Data, Open Access, OAI-PMH, Dataverse, France

## APIs

- **HAL Sorbonne Université Open Archive (OAI-PMH)** — Harvestable metadata for the institution's open archive of scholarly publications, served via the standards-based OAI-PMH protocol on the central HAL infrastructure. Docs: https://api.archives-ouvertes.fr/docs/oai — Portal: https://hal.sorbonne-universite.fr/
- **HAL Search API** — Solr-based search over the HAL corpus including Sorbonne Université publications. Docs: https://api.archives-ouvertes.fr/docs/search
- **Recherche Data Gouv Dataverse — Sorbonne Université Collection** — Live Dataverse 6.0 Native REST API exposing the university's research-data collection on the French national repository. Docs: https://guides.dataverse.org/en/latest/api/native-api.html — Collection: https://entrepot.recherche.data.gouv.fr/dataverse/sorbonne-univ

## Plans

See [plans/sorbonne-plans-pricing.yml](plans/sorbonne-plans-pricing.yml).

## Rate Limits

See [rate-limits/sorbonne-rate-limits.yml](rate-limits/sorbonne-rate-limits.yml).

## FinOps

See [finops/sorbonne-finops.yml](finops/sorbonne-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.sorbonne-universite.fr/en
- GitHub: https://github.com/sorbonne-universite
- LinkedIn: https://www.linkedin.com/school/sorbonne-universite/

## Notes

Sorbonne University does not operate a centralized public developer portal. The APIs cataloged here are standards-based open-science interfaces verified reachable on 2026-06-03: the central HAL OAI-PMH endpoint (valid Identify response) and the Recherche Data Gouv Dataverse Native API (version 6.0, status OK). The institutional HAL web front end (hal.sorbonne-universite.fr) is behind Anubis bot protection, but its data remains harvestable through the central HAL API. The official GitHub org (sorbonne-universite) is legitimate but currently has no public repositories. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
