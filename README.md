# Semantic Scholar (semantic-scholar)

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
