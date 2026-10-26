# Semantic Scholar (semantic-scholar)

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

Semantic Scholar is a free, AI-powered academic search engine developed by the Allen Institute for AI (AI2) that indexes over 214 million scholarly papers with 2.49 billion citations and 79 million authors. The platform exposes a public REST API organized into three services: Academic Graph (papers, authors, citations, venues, and SPECTER2 embeddings), Recommendations (paper similarity and interest-based suggestions), and Datasets (bulk downloadable corpus snapshots updated monthly). API access is available without authentication at a shared rate limit, or with a free institutional API key for a dedicated 1 RPS allowance. Semantic Scholar is widely used in academic research tooling and supports AI agent integrations through multiple community-built MCP servers.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/semantic-scholar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/semantic-scholar/refs/heads/main/apis.yml)

Manage APIs like this one with [Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=semantic-scholar-api-evangelist&utm_content=repo).

## Tags

- Academic
- Research
- Papers
- Citations
- Authors
- Scientific Literature
- AI
- Recommendations

## APIs

| Name | Base URL | Documentation |
|---|---|---|
| Academic Graph API | https://api.semanticscholar.org/graph/v1 | https://api.semanticscholar.org/api-docs/ |
| Recommendations API | https://api.semanticscholar.org/recommendations/v1 | https://api.semanticscholar.org/api-docs/recommendations |
| Datasets API | https://api.semanticscholar.org/datasets/v1 | https://api.semanticscholar.org/api-docs/ |

## Plans / Rate Limits / FinOps

| Resource | Path |
|---|---|
| Plans & Pricing | [plans/semantic-scholar-plans-pricing.yml](plans/semantic-scholar-plans-pricing.yml) |
| Rate Limits | [rate-limits/semantic-scholar-rate-limits.yml](rate-limits/semantic-scholar-rate-limits.yml) |
| FinOps | [finops/semantic-scholar-finops.yml](finops/semantic-scholar-finops.yml) |

### Summary

- **Billing Model:** Free (freemium)
- **Unauthenticated:** 100 requests per 5 minutes (shared pool)
- **Authenticated (API Key):** 1 RPS dedicated; free key via institutional email request
- **Datasets:** Free bulk corpus downloads with API key; monthly snapshots with diff support

## Timestamps

| Field | Value |
|---|---|
| Created | 2026-06-12 |
| Modified | 2026-06-12 |

## Common Properties

| Type | URL |
|---|---|
| Website | https://www.semanticscholar.org |
| Documentation | https://www.semanticscholar.org/product/api |
| GitHub Organization | https://github.com/allenai |
| GitHub Repository (s2-folks) | https://github.com/allenai/s2-folks |
| Blog | https://medium.com/ai2-blog/semantic-scholar/home |
| Status Page | https://status.api.semanticscholar.org/ |
| X / Twitter | https://twitter.com/SemanticScholar |
| Tutorial | https://www.semanticscholar.org/product/api/tutorial |
| Terms of Service / License | https://www.semanticscholar.org/product/api/license |
| Privacy Policy | https://www.semanticscholar.org/privacy-policy |

## Maintainers

| Name | Email |
|---|---|
| Kin Lane | kin@apievangelist.com |
