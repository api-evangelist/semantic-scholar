# Semantic Scholar

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

Semantic Scholar is a free, AI-powered academic search engine developed by the Allen Institute for AI (AI2) that indexes over 214 million scholarly papers with 2.49 billion citations and 79 million authors. The platform provides a public REST API organized into three services: Academic Graph (papers, authors, citations, venues, and SPECTER2 embeddings), Recommendations (paper similarity and interest-based suggestions), and Datasets (bulk downloadable corpus snapshots updated monthly). API access is available without authentication at a shared rate limit, or with a free API key obtained via request for a dedicated 1 RPS allowance. Semantic Scholar supports AI agent integrations through multiple community-built MCP servers that expose its academic graph to LLM-based toolchains.

**Areas:** Academic · Research · Paper · Citations · Authors · Scientific Literature · Artificial Intelligence · Recommendations · Research Data · Open Access

## Semantic Scholar on APIs.io

Everything profiled for Semantic Scholar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/semantic-scholar/](https://apis.io/providers/semantic-scholar/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Semantic Scholar Author Data API](https://apis.io/apis/semantic-scholar/semantic-scholar-author-data-api/) — The Author Data API from Semantic Scholar — 4 operation(s) for author data.
- [Semantic Scholar Incremental Updates API](https://apis.io/apis/semantic-scholar/semantic-scholar-incremental-updates-api/) — The Incremental Updates API from Semantic Scholar — 1 operation(s) for incremental updates.
- [Semantic Scholar Paper Data API](https://apis.io/apis/semantic-scholar/semantic-scholar-paper-data-api/) — The Paper Data API from Semantic Scholar — 9 operation(s) for paper data.
- [Semantic Scholar Paper Recommendations API](https://apis.io/apis/semantic-scholar/semantic-scholar-paper-recommendations-api/) — The Paper Recommendations API from Semantic Scholar — 2 operation(s) for paper recommendations.
- [Semantic Scholar Release Data API](https://apis.io/apis/semantic-scholar/semantic-scholar-release-data-api/) — The Release Data API from Semantic Scholar — 3 operation(s) for release data.
- [Semantic Scholar Snippet Text API](https://apis.io/apis/semantic-scholar/semantic-scholar-snippet-text-api/) — The Snippet Text API from Semantic Scholar — 1 operation(s) for snippet text.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [semantic-scholar](https://apis.io/servers/semantic-scholar/semantic-scholar/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Semantic Scholar Agentic Access](https://apis.io/agentic-access/semantic-scholar/semantic-scholar-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [AuthorWithPapers](https://apis.io/schemas/semantic-scholar/semantic-scholar-author/)
- [Citation](https://apis.io/schemas/semantic-scholar/semantic-scholar-citation/)
- [Release Metadata](https://apis.io/schemas/semantic-scholar/semantic-scholar-dataset-release/)
- [FullPaper](https://apis.io/schemas/semantic-scholar/semantic-scholar-paper/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Semantic Scholar Context](https://apis.io/jsonld/semantic-scholar/semantic-scholar-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Semantic Scholar Vocabulary](https://apis.io/vocabularies/semantic-scholar/semantic-scholar-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Semantic Scholar Datasets Releases Example](https://apis.io/examples/semantic-scholar/semantic-scholar-datasets-releases-example/)
- [Semantic Scholar Paper Search Example](https://apis.io/examples/semantic-scholar/semantic-scholar-paper-search-example/)
- [Semantic Scholar Recommendations Example](https://apis.io/examples/semantic-scholar/semantic-scholar-recommendations-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Academic Graph Author Data API](https://apis.io/collections/semantic-scholar/open-semantic-scholar-author-data-api/)
- [Academic Graph Author Data Incremental Updates API](https://apis.io/collections/semantic-scholar/open-semantic-scholar-incremental-updates-api/)
- [Academic Graph Author Data Paper Data API](https://apis.io/collections/semantic-scholar/open-semantic-scholar-paper-data-api/)
- [Academic Graph Author Data Paper Recommendations API](https://apis.io/collections/semantic-scholar/open-semantic-scholar-paper-recommendations-api/)
- [Academic Graph Author Data Release Data API](https://apis.io/collections/semantic-scholar/open-semantic-scholar-release-data-api/)
- [Academic Graph Author Data Snippet Text API](https://apis.io/collections/semantic-scholar/open-semantic-scholar-snippet-text-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Semantic Scholar — jsonschema rules](https://apis.io/rules/semantic-scholar/semantic-scholar-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Semantic Scholar Domain Security](https://apis.io/security/semantic-scholar/semantic-scholar-domain-security/)
- [Semantic Scholar Vulnerability Disclosure](https://apis.io/security/semantic-scholar/semantic-scholar-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Semantic Scholar Plans Pricing](https://apis.io/plans/semantic-scholar/semantic-scholar-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Semantic Scholar Rate Limits](https://apis.io/rate-limits/semantic-scholar/semantic-scholar-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Semantic Scholar Finops](https://apis.io/finops/semantic-scholar/semantic-scholar-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.semanticscholar.org)
- [Documentation](https://www.semanticscholar.org/product/api)
- [Pricing](https://www.semanticscholar.org/product/api)
- [Blog](https://medium.com/ai2-blog/semantic-scholar/home)
- [Terms of service](https://www.semanticscholar.org/product/api/license)
- [Privacy policy](https://www.semanticscholar.org/privacy-policy)
- [GitHub](https://github.com/allenai)
- [Status](https://status.api.semanticscholar.org/)

## API Evangelist rating

**Kin Score 33.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.3 |
| Contract quality | 48.5 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 11.9 |
| Access clarity | 28.9 |

**Agent readiness 34.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 19.1** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/semantic-scholar/](https://apis.io/providers/semantic-scholar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Semantic Scholar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/semantic-scholar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
