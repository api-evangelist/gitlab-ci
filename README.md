# GitLab CI/CD (gitlab-ci)

GitLab CI/CD is the built-in continuous integration, delivery and deployment platform for GitLab. The CI/CD surface area within GitLab's REST API v4 covers pipelines, jobs, pipeline schedules, pipeline triggers, runners, agents, releases, environments, deployments, package and container registries, and the security/dependency scanners. GitLab also exposes a GraphQL API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gitlab-ci/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gitlab-ci/refs/heads/main/apis.yml)

## Tags

- DevOps
- CI/CD
- Pipelines
- GitLab
- DevSecOps
- Runners
- Container Registry

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### GitLab REST API v4 (CI/CD endpoints)

GitLab REST API v4. CI/CD-related endpoint families include /projects/:id/ pipelines, /projects/:id/jobs, /projects/:id/pipeline_schedules, /projects/:id/triggers, /runners, /projects/:id/runners, /projects/:id/environments, /projects/:id/deployments and the /projects/:id/releases family. Authenticated with personal access tokens, OAuth tokens, project access tokens, group access tokens, CI job tokens or trigger tokens.

- **Human URL:** [https://docs.gitlab.com/api/](https://docs.gitlab.com/api/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- REST
- Pipelines
- Jobs
- Runners
- Schedules
- Releases

#### Properties

- [Documentation](https://docs.gitlab.com/api/)
- [API Reference](https://docs.gitlab.com/api/api_resources/)
- [OpenAPI](openapi/gitlab-ci-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitlab-ci.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-ci.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Source](https://docs.gitlab.com/api/openapi/openapi_v2.yaml)
- [Interactive Docs](https://docs.gitlab.com/api/openapi/openapi_interactive/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)

### GitLab GraphQL API

GitLab's GraphQL API at /api/graphql. Many CI/CD entities (Pipeline, CiJob, CiRunner, MergeRequest pipelines) are exposed via GraphQL queries and mutations.

- **Human URL:** [https://docs.gitlab.com/api/graphql/](https://docs.gitlab.com/api/graphql/)
- **Base URL:** `https://gitlab.com/api/graphql`

#### Tags

- GraphQL
- Pipelines
- Jobs

#### Properties

- [Documentation](https://docs.gitlab.com/api/graphql/)
- [Graph Q L Explorer](https://gitlab.com/-/graphql-explorer)
- [Reference](https://docs.gitlab.com/api/graphql/reference/)
- [Postman Collection](collections/gitlab-ci.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-ci.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://about.gitlab.com/)
- [Documentation](https://docs.gitlab.com/api/)
- [Pricing](https://about.gitlab.com/pricing/)
- [Git Hub](https://gitlab.com/gitlab-org/gitlab)
- [Status Page](https://status.gitlab.com/)
- [Plans](plans/gitlab-ci-plans-pricing.yml)
- [Rate Limits](rate-limits/gitlab-ci-rate-limits.yml)
- [Fin Ops](finops/gitlab-ci-finops.yml)
- [L L Ms Txt](https://docs.gitlab.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
