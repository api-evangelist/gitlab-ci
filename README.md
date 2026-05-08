# GitLab CI/CD (gitlab-ci)

GitLab CI/CD is the built-in continuous integration, delivery and deployment platform for GitLab. The CI/CD surface area is exposed through GitLab's REST API v4 and GraphQL API: pipelines, jobs, schedules, triggers, runners, environments, deployments, releases, container/package registries and security scanners.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **REST v4** — `https://gitlab.com/api/v4` — pipelines, jobs, runners, triggers, schedules, releases, environments, deployments. [Docs](https://docs.gitlab.com/api/) · [OpenAPI](openapi/gitlab-ci-openapi.yml)
- **GraphQL** — `https://gitlab.com/api/graphql` — Pipeline, CiJob, CiRunner, MergeRequest pipelines. [Docs](https://docs.gitlab.com/api/graphql/)

## OpenAPI (fetched 2026-05-08)
`openapi/gitlab-ci-openapi.yml` — auto-generated v2 spec, source <https://docs.gitlab.com/api/openapi/openapi_v2.yaml> (~2.2 MB; partial coverage of v4 endpoints — GitLab is still expanding it).

## Tags
DevOps, CI/CD, Pipelines, GitLab, DevSecOps, Runners, Container Registry

## Common Properties
- [Website](https://about.gitlab.com/) · [Docs](https://docs.gitlab.com/api/) · [Pricing](https://about.gitlab.com/pricing/)
- [Source](https://gitlab.com/gitlab-org/gitlab) · [Status](https://status.gitlab.com/)
- [Plans](plans/gitlab-ci-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/gitlab-ci-rate-limits.yml) — reconciled
- [FinOps](finops/gitlab-ci-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Free** — 400 CI compute min/user/mo, 10 GiB storage.
- **Premium** — $29/user/mo (annual), 10,000 CI min/user/mo, 500 GiB.
- **Ultimate** — custom, 50,000 CI min/user/mo, 500 GiB.
- **Compute top-up** — $10 per 1,000 minutes (one-time).
- **Self-Managed / Dedicated** — custom contracts.

## Rate Limits (reconciled)
- Search: 30/min auth, 10/min unauth.
- Autocomplete users: 300/min auth, 100/min unauth.
- Raw blob: 300/min per project+path; 800/min per project unauth.
- Default API: 500/min unauth, 2,000/min auth.
- 429 with `Retry-After` and `RateLimit-*` headers.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
