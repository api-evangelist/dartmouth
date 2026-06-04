# Dartmouth College (dartmouth)

Dartmouth College is a private Ivy League research university in Hanover, New Hampshire, United States, ranked #243 in the QS World University Rankings 2025. This repository catalogs Dartmouth's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/dartmouth/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=dartmouth-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Artificial Intelligence, United States, Ivy League

## APIs

- **DartAPI Developer Portal** — Institutional resource APIs (People/directory, Nextgen) gated behind Dartmouth CAS SSO and manually issued, JWT-based API keys. Docs: https://developer.dartmouth.edu/
- **Dartmouth Chat AI API** — OpenAI-compatible REST API for Dartmouth-hosted LLMs, embeddings, and reranking models, plus selected cloud models. Base: `https://chat.dartmouth.edu/api`. Docs: https://rc.dartmouth.edu/ai/online-resources/using-the-api/ — SDK: https://pypi.org/project/langchain-dartmouth/ — GitHub: https://github.com/dartmouth/langchain-dartmouth
- **Dartmouth Open Data (ArcGIS Hub)** — Public geospatial/tabular datasets via ArcGIS Hub Search API and per-dataset ArcGIS REST/GeoJSON services. Docs: https://data-dartmouth.opendata.arcgis.com/

## Plans

- [plans/dartmouth-plans-pricing.yml](plans/dartmouth-plans-pricing.yml)

## Rate Limits

- [rate-limits/dartmouth-rate-limits.yml](rate-limits/dartmouth-rate-limits.yml)

## FinOps

- [finops/dartmouth-finops.yml](finops/dartmouth-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://home.dartmouth.edu/
- GitHub: https://github.com/dartmouth
- GitHub (Digital Library Technologies Group): https://github.com/dartmouth-dltg
- Developer Portal: https://developer.dartmouth.edu/
- LinkedIn: https://www.linkedin.com/school/dartmouth-college/
- Twitter/X: https://x.com/dartmouth
- Authentication (CAS SSO): https://login.dartmouth.edu/cas/login

## Notes

Verification caveats: The DartAPI developer portal and its documented resource APIs (People, Nextgen) appear in search results but the portal and docs pages return HTTP 302 redirects to Dartmouth CAS login — they are gated and API keys are issued manually, so endpoints were not independently confirmed and none were fabricated. The Dartmouth Chat AI API (`https://chat.dartmouth.edu/api`, 200) and the ArcGIS Hub open-data portal (200) were verified live and are documented publicly. GitHub organizations `dartmouth` and `dartmouth-dltg` are public and active.

## Maintainers

- Kin Lane — kin@apievangelist.com
