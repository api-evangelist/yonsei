# Yonsei University (yonsei)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
