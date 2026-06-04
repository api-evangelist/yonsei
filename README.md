# Yonsei University (yonsei)

Yonsei University is a private research university in Seoul, South Korea, founded in 1885 and ranked #73 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer and API footprint as an [APIs.json](https://apievangelist.com/apis-json/) provider profile. That footprint is limited: the research portal runs on Elsevier Pure (OAI-PMH/REST present but gated), and the medical library runs a DSpace institutional repository (RSS public, OAI/REST not currently reachable). No official open developer portal was confirmed.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/yonsei/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=yonsei-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Repository, South Korea, Seoul

## APIs

- **Yonsei Research Information Portal (Elsevier Pure)** — Research outputs, profiles, projects, and organizations on Elsevier Pure. Pure OAI-PMH (`/ws/oai`) and REST (`/ws/api`) endpoints exist but return HTTP 401 (gated). Docs: https://yonsei.elsevierpure.com/
- **YUHSpace Institutional Repository (DSpace)** — Yonsei University Health System / Medical Library DSpace 5.5 repository (built via the National Library of Korea OAK project). Public RSS feed reachable; OAI-PMH/REST paths return HTTP 404. Docs: https://ir.ymlib.yonsei.ac.kr/ — RSS: https://ir.ymlib.yonsei.ac.kr/feed/rss_2.0/site

## Plans

- [plans/yonsei-plans-pricing.yml](plans/yonsei-plans-pricing.yml)

## Rate Limits

- [rate-limits/yonsei-rate-limits.yml](rate-limits/yonsei-rate-limits.yml)

## FinOps

- [finops/yonsei-finops.yml](finops/yonsei-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.yonsei.ac.kr/
- GitHub: https://github.com/gdg-yonsei (student Google Developer Group, not an official institutional API org)
- LinkedIn: https://www.linkedin.com/school/yonsei/
- Plans, Rate Limits, FinOps, Review pointers (see files above and [review.yml](review.yml))

## Notes

All entries are based on live verification on 2026-06-03; no endpoints were fabricated. The Elsevier Pure OAI-PMH and REST endpoints exist but are gated (HTTP 401). The YUHSpace DSpace repository is live with a working RSS feed, but its OAI-PMH and REST paths did not resolve publicly (HTTP 404). No official, documented public developer portal or open API was found. See [review.yml](review.yml) for the full list of probed URLs and their HTTP statuses.

## Maintainers

- Kin Lane — kin@apievangelist.com
