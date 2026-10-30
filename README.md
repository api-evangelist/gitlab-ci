# GitLab CI/CD

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

GitLab CI/CD is the built-in continuous integration, delivery and deployment platform for GitLab. The CI/CD surface area within GitLab's REST API v4 covers pipelines, jobs, pipeline schedules, pipeline triggers, runners, agents, releases, environments, deployments, package and container registries, and the security/dependency scanners. GitLab also exposes a GraphQL API.

**Areas:** DevOps · CI/CD · Pipelines · GitLab · DevSecOps · Runners · Container Registry · Developer Tools

## GitLab CI/CD on APIs.io

Everything profiled for GitLab CI/CD is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gitlab-ci/](https://apis.io/providers/gitlab-ci/)** — or go straight to one of the APIs or properties below.

### APIs (98)

- [GitLab GraphQL API](https://apis.io/apis/gitlab-ci/graphql/) — GitLab's GraphQL API at /api/graphql. Many CI/CD entities (Pipeline, CiJob, CiRunner, MergeRequest pipelines) are exposed via GraphQL queries and mutations.
- [GitLab CI/CD access_requests API](https://apis.io/apis/gitlab-ci/gitlab-ci-access-requests-api/) — Operations related to access requests
- [GitLab CI/CD access_tokens API](https://apis.io/apis/gitlab-ci/gitlab-ci-access-tokens-api/) — Operations about access_tokens
- [GitLab CI/CD Agents API](https://apis.io/apis/gitlab-ci/gitlab-ci-agents-api/) — Operations about agents
- [GitLab CI/CD Alert Management API](https://apis.io/apis/gitlab-ci/gitlab-ci-alert-management-api/) — Operations about alert_managements
- [GitLab CI/CD Applications API](https://apis.io/apis/gitlab-ci/gitlab-ci-applications-api/) — Operations about applications
- [GitLab CI/CD Attestations API](https://apis.io/apis/gitlab-ci/gitlab-ci-attestations-api/) — Operations about attestations
- [GitLab CI/CD Audit Events API](https://apis.io/apis/gitlab-ci/gitlab-ci-audit-events-api/) — Operations about audit_events
- [GitLab CI/CD Avatars API](https://apis.io/apis/gitlab-ci/gitlab-ci-avatars-api/) — Operations about avatars
- [GitLab CI/CD Award Emoji API](https://apis.io/apis/gitlab-ci/gitlab-ci-award-emoji-api/) — Operations about award_emoji
- [GitLab CI/CD Badges API](https://apis.io/apis/gitlab-ci/gitlab-ci-badges-api/) — Operations about badges
- [GitLab CI/CD Batched Background Migrations API](https://apis.io/apis/gitlab-ci/gitlab-ci-batched-background-migrations-api/) — Operations about batched_background_migrations
- [GitLab CI/CD Branches API](https://apis.io/apis/gitlab-ci/gitlab-ci-branches-api/) — Operations about branches
- [GitLab CI/CD Broadcast Messages API](https://apis.io/apis/gitlab-ci/gitlab-ci-broadcast-messages-api/) — Operations about broadcast_messages
- [GitLab CI/CD Chaos API](https://apis.io/apis/gitlab-ci/gitlab-ci-chaos-api/) — Operations about chaos
- [GitLab CI/CD Ci Catalog API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-catalog-api/) — Operations about ci_catalogs
- [GitLab CI/CD Ci Jobs API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-jobs-api/) — Operations about ci_jobs
- [GitLab CI/CD Ci Lint API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-lint-api/) — Operations related to linting a CI config file
- [GitLab CI/CD Ci Resource Groups API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-resource-groups-api/) — Operations to manage job concurrency with resource groups
- [GitLab CI/CD Ci Runners API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-runners-api/) — Operations about ci_runners
- [GitLab CI/CD Ci Triggers API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-triggers-api/) — Operations about ci_triggers
- [GitLab CI/CD Ci Variables API](https://apis.io/apis/gitlab-ci/gitlab-ci-ci-variables-api/) — Operations related to CI/CD variables
- [GitLab CI/CD Cluster Agents API](https://apis.io/apis/gitlab-ci/gitlab-ci-cluster-agents-api/) — Operations related to the GitLab agent for Kubernetes
- [GitLab CI/CD Clusters API](https://apis.io/apis/gitlab-ci/gitlab-ci-clusters-api/) — Operations related to clusters
- [GitLab CI/CD Commit Statuses API](https://apis.io/apis/gitlab-ci/gitlab-ci-commit-statuses-api/) — Operations about commit_statuses
- [GitLab CI/CD Commits API](https://apis.io/apis/gitlab-ci/gitlab-ci-commits-api/) — Operations about commits
- [GitLab CI/CD Container Registry API](https://apis.io/apis/gitlab-ci/gitlab-ci-container-registry-api/) — Operations related to container registry
- [GitLab CI/CD Custom Attributes API](https://apis.io/apis/gitlab-ci/gitlab-ci-custom-attributes-api/) — Operations about custom_attributes
- [GitLab CI/CD Database Dictionary API](https://apis.io/apis/gitlab-ci/gitlab-ci-database-dictionary-api/) — Operations about database_dictionaries
- [GitLab CI/CD Dependency Proxy API](https://apis.io/apis/gitlab-ci/gitlab-ci-dependency-proxy-api/) — Operations to manage dependency proxy for a groups
- [GitLab CI/CD Deploy Resources API](https://apis.io/apis/gitlab-ci/gitlab-ci-deploy-resources-api/) — Operations about deploy_resources
- [GitLab CI/CD Draft Notes API](https://apis.io/apis/gitlab-ci/gitlab-ci-draft-notes-api/) — Operations about draft_notes
- [GitLab CI/CD Environments API](https://apis.io/apis/gitlab-ci/gitlab-ci-environments-api/) — Operations related to environments
- [GitLab CI/CD Error Tracking API](https://apis.io/apis/gitlab-ci/gitlab-ci-error-tracking-api/) — Operations about error_trackings
- [GitLab CI/CD Events API](https://apis.io/apis/gitlab-ci/gitlab-ci-events-api/) — Operations about events
- [GitLab CI/CD Feature Flags API](https://apis.io/apis/gitlab-ci/gitlab-ci-feature-flags-api/) — Operations related to feature flags
- [GitLab CI/CD Features API](https://apis.io/apis/gitlab-ci/gitlab-ci-features-api/) — Operations related to managing Flipper-based feature flags
- [GitLab CI/CD Files API](https://apis.io/apis/gitlab-ci/gitlab-ci-files-api/) — Operations about files
- [GitLab CI/CD Freeze Periods API](https://apis.io/apis/gitlab-ci/gitlab-ci-freeze-periods-api/) — Operations related to deploy freeze periods
- [GitLab CI/CD Geo API](https://apis.io/apis/gitlab-ci/gitlab-ci-geo-api/) — Operations related to Geo
- [GitLab CI/CD Gitlab Pages API](https://apis.io/apis/gitlab-ci/gitlab-ci-gitlab-pages-api/) — Operations about gitlab_pages
- [GitLab CI/CD Glql API](https://apis.io/apis/gitlab-ci/gitlab-ci-glql-api/) — Operations about glqls
- [GitLab CI/CD Group Import And Export API](https://apis.io/apis/gitlab-ci/gitlab-ci-group-import-and-export-api/) — Operations about group_import_and_exports
- [GitLab CI/CD Groups API](https://apis.io/apis/gitlab-ci/gitlab-ci-groups-api/) — Operations about groups
- [GitLab CI/CD Hooks API](https://apis.io/apis/gitlab-ci/gitlab-ci-hooks-api/) — Operations about hooks
- [GitLab CI/CD Imports API](https://apis.io/apis/gitlab-ci/gitlab-ci-imports-api/) — Operations about imports
- [GitLab CI/CD Instance API](https://apis.io/apis/gitlab-ci/gitlab-ci-instance-api/) — Operations about instances
- [GitLab CI/CD Integrations API](https://apis.io/apis/gitlab-ci/gitlab-ci-integrations-api/) — Operations related to integrations
- [GitLab CI/CD Internal Operations API](https://apis.io/apis/gitlab-ci/gitlab-ci-internal-operations-api/) — Operations about internal_operations
- [GitLab CI/CD Invitations API](https://apis.io/apis/gitlab-ci/gitlab-ci-invitations-api/) — Operations about invitations
- [GitLab CI/CD Issues API](https://apis.io/apis/gitlab-ci/gitlab-ci-issues-api/) — Operations about issues
- [GitLab CI/CD Jira Connect Subscriptions API](https://apis.io/apis/gitlab-ci/gitlab-ci-jira-connect-subscriptions-api/) — Operations related to JiraConnect subscriptions
- [GitLab CI/CD Job Artifacts API](https://apis.io/apis/gitlab-ci/gitlab-ci-job-artifacts-api/) — Operations about job_artifacts
- [GitLab CI/CD Jobs API](https://apis.io/apis/gitlab-ci/gitlab-ci-jobs-api/) — Operations about jobs
- [GitLab CI/CD Keys API](https://apis.io/apis/gitlab-ci/gitlab-ci-keys-api/) — Operations about keys
- [GitLab CI/CD Ldap API](https://apis.io/apis/gitlab-ci/gitlab-ci-ldap-api/) — Operations about ldaps
- [GitLab CI/CD Markdown API](https://apis.io/apis/gitlab-ci/gitlab-ci-markdown-api/) — Operations about markdowns
- [GitLab CI/CD Members API](https://apis.io/apis/gitlab-ci/gitlab-ci-members-api/) — Operations about members
- [GitLab CI/CD Merge Request Approvals API](https://apis.io/apis/gitlab-ci/gitlab-ci-merge-request-approvals-api/) — Operations about merge_request_approvals
- [GitLab CI/CD Merge Requests API](https://apis.io/apis/gitlab-ci/gitlab-ci-merge-requests-api/) — Operations related to merge requests
- [GitLab CI/CD Metadata API](https://apis.io/apis/gitlab-ci/gitlab-ci-metadata-api/) — Operations related to metadata of the GitLab instance
- [GitLab CI/CD Metric Images API](https://apis.io/apis/gitlab-ci/gitlab-ci-metric-images-api/) — Operations about metric_images
- [GitLab CI/CD Metrics API](https://apis.io/apis/gitlab-ci/gitlab-ci-metrics-api/) — Operations about metrics
- [GitLab CI/CD Migrations API](https://apis.io/apis/gitlab-ci/gitlab-ci-migrations-api/) — Operations about migrations
- [GitLab CI/CD Ml Model Registry API](https://apis.io/apis/gitlab-ci/gitlab-ci-ml-model-registry-api/) — Operations related to Model registry
- [GitLab CI/CD Namespaces API](https://apis.io/apis/gitlab-ci/gitlab-ci-namespaces-api/) — Operations about namespaces
- [GitLab CI/CD Offline Transfers API](https://apis.io/apis/gitlab-ci/gitlab-ci-offline-transfers-api/) — Operations about offline_transfers
- [GitLab CI/CD Organizations API](https://apis.io/apis/gitlab-ci/gitlab-ci-organizations-api/) — Operations about organizations
- [GitLab CI/CD Packages API](https://apis.io/apis/gitlab-ci/gitlab-ci-packages-api/) — Operations about packages
- [GitLab CI/CD Pipeline Schedules API](https://apis.io/apis/gitlab-ci/gitlab-ci-pipeline-schedules-api/) — Operations about pipeline_schedules
- [GitLab CI/CD Pipelines API](https://apis.io/apis/gitlab-ci/gitlab-ci-pipelines-api/) — Operations about pipelines
- [GitLab CI/CD Plan Limits API](https://apis.io/apis/gitlab-ci/gitlab-ci-plan-limits-api/) — Operations related to plan limits
- [GitLab CI/CD Project Import API](https://apis.io/apis/gitlab-ci/gitlab-ci-project-import-api/) — Operations related to importing projects
- [GitLab CI/CD Project Snapshots API](https://apis.io/apis/gitlab-ci/gitlab-ci-project-snapshots-api/) — Operations about project_snapshots
- [GitLab CI/CD Project Templates API](https://apis.io/apis/gitlab-ci/gitlab-ci-project-templates-api/) — Operations about project_templates
- [GitLab CI/CD Project Topics API](https://apis.io/apis/gitlab-ci/gitlab-ci-project-topics-api/) — Operations about project_topics
- [GitLab CI/CD Projects API](https://apis.io/apis/gitlab-ci/gitlab-ci-projects-api/) — Operations related to projects
- [GitLab CI/CD Projects Job Token Scope API](https://apis.io/apis/gitlab-ci/gitlab-ci-projects-job-token-scope-api/) — Operations about projects_job_token_scopes
- [GitLab CI/CD Protected Branches API](https://apis.io/apis/gitlab-ci/gitlab-ci-protected-branches-api/) — Operations about protected_branches
- [GitLab CI/CD Protected Tags API](https://apis.io/apis/gitlab-ci/gitlab-ci-protected-tags-api/) — Operations about protected_tags
- [GitLab CI/CD Pypi Packages API](https://apis.io/apis/gitlab-ci/gitlab-ci-pypi-packages-api/) — Operations related to PyPI packages
- [GitLab CI/CD Releases API](https://apis.io/apis/gitlab-ci/gitlab-ci-releases-api/) — Operations related to releases
- [GitLab CI/CD Remote Mirrors API](https://apis.io/apis/gitlab-ci/gitlab-ci-remote-mirrors-api/) — Operations about remote_mirrors
- [GitLab CI/CD Repositories API](https://apis.io/apis/gitlab-ci/gitlab-ci-repositories-api/) — Operations about repositories
- [GitLab CI/CD Resource Events API](https://apis.io/apis/gitlab-ci/gitlab-ci-resource-events-api/) — Operations about resource_events
- [GitLab CI/CD Runners API](https://apis.io/apis/gitlab-ci/gitlab-ci-runners-api/) — Operations about runners
- [GitLab CI/CD Search API](https://apis.io/apis/gitlab-ci/gitlab-ci-search-api/) — Operations about searches
- [GitLab CI/CD Secure Files API](https://apis.io/apis/gitlab-ci/gitlab-ci-secure-files-api/) — Operations about secure_files
- [GitLab CI/CD Snippets API](https://apis.io/apis/gitlab-ci/gitlab-ci-snippets-api/) — Operations about snippets
- [GitLab CI/CD Submodules API](https://apis.io/apis/gitlab-ci/gitlab-ci-submodules-api/) — Operations about submodules
- [GitLab CI/CD Suggestions API](https://apis.io/apis/gitlab-ci/gitlab-ci-suggestions-api/) — Operations related to suggestions
- [GitLab CI/CD Tags API](https://apis.io/apis/gitlab-ci/gitlab-ci-tags-api/) — Operations about tags
- [GitLab CI/CD Terraform API](https://apis.io/apis/gitlab-ci/gitlab-ci-terraform-api/) — Operations about terraforms
- [GitLab CI/CD Unleash API](https://apis.io/apis/gitlab-ci/gitlab-ci-unleash-api/) — Operations about unleashes
- [GitLab CI/CD Usage Data API](https://apis.io/apis/gitlab-ci/gitlab-ci-usage-data-api/) — Operations about usage_data
- [GitLab CI/CD Users API](https://apis.io/apis/gitlab-ci/gitlab-ci-users-api/) — Operations about users
- [GitLab CI/CD Web Commits API](https://apis.io/apis/gitlab-ci/gitlab-ci-web-commits-api/) — Operations about web_commits
- [GitLab CI/CD Wikis API](https://apis.io/apis/gitlab-ci/gitlab-ci-wikis-api/) — Operations about wikis

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [GitLab CI/CD GraphQL API](https://apis.io/graphqls/gitlab-ci/gitlab-ci-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [gitlab-ci](https://apis.io/servers/gitlab-ci/gitlab-ci/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gitlab Ci Agentic Access](https://apis.io/agentic-access/gitlab-ci/gitlab-ci-agentic-access/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Gitlab Ci Structure](https://apis.io/json-structure/gitlab-ci/gitlab-ci-structure/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [GitLab CI/CD Domain Vocabulary](https://apis.io/vocabularies/gitlab-ci/gitlab-ci-vocabulary/)

#### Collections (98)

Postman and Open Collection request collections.

- [GitLab API](https://apis.io/collections/gitlab-ci/open-gitlab-ci/)
- [GitLab access_requests API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-access-requests-api/)
- [GitLab access_requests access_tokens API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-access-tokens-api/)
- [GitLab access_requests agents API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-agents-api/)
- [GitLab access_requests alert_management API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-alert-management-api/)
- [GitLab access_requests applications API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-applications-api/)
- [GitLab access_requests attestations API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-attestations-api/)
- [GitLab access_requests audit_events API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-audit-events-api/)
- [GitLab access_requests avatars API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-avatars-api/)
- [GitLab access_requests award_emoji API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-award-emoji-api/)
- [GitLab access_requests badges API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-badges-api/)
- [GitLab access_requests batched_background_migrations API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-batched-background-migrations-api/)
- [GitLab access_requests branches API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-branches-api/)
- [GitLab access_requests broadcast_messages API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-broadcast-messages-api/)
- [GitLab access_requests chaos API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-chaos-api/)
- [GitLab access_requests ci_catalog API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-catalog-api/)
- [GitLab access_requests ci_jobs API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-jobs-api/)
- [GitLab access_requests ci_lint API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-lint-api/)
- [GitLab access_requests ci_resource_groups API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-resource-groups-api/)
- [GitLab access_requests ci_runners API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-runners-api/)
- [GitLab access_requests ci_triggers API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-triggers-api/)
- [GitLab access_requests ci_variables API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-ci-variables-api/)
- [GitLab access_requests cluster_agents API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-cluster-agents-api/)
- [GitLab access_requests clusters API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-clusters-api/)
- [GitLab access_requests commit_statuses API](https://apis.io/collections/gitlab-ci/open-gitlab-ci-commit-statuses-api/)
- …and 73 more published on APIs.io

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Gitlab Ci Authentication](https://apis.io/security/gitlab-ci/gitlab-ci-authentication/)
- [Gitlab Ci Domain Security](https://apis.io/security/gitlab-ci/gitlab-ci-domain-security/)
- [Gitlab Ci Trust Center](https://apis.io/security/gitlab-ci/gitlab-ci-trust-center/)
- [Gitlab Ci Vulnerability Disclosure](https://apis.io/security/gitlab-ci/gitlab-ci-vulnerability-disclosure/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Gitlab Ci Plans Pricing](https://apis.io/plans/gitlab-ci/gitlab-ci-plans-pricing/)
- [Gitlab Ci Price Estimates](https://apis.io/plans/gitlab-ci/gitlab-ci-price-estimates/)

#### Rate limits (1)

Published request limits.

- [Gitlab Ci Rate Limits](https://apis.io/rate-limits/gitlab-ci/gitlab-ci-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Gitlab Ci Finops](https://apis.io/finops/gitlab-ci/gitlab-ci-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://about.gitlab.com/)
- [Documentation](https://docs.gitlab.com/api/)
- [Pricing](https://about.gitlab.com/pricing/)
- [Blog](https://about.gitlab.com/atom.xml)
- [Status](https://status.gitlab.com/)

## API Evangelist rating

**Kin Score 45.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 44.6 |
| Contract governance | 0.0 |
| Operational transparency | 52.6 |
| Developer ergonomics | 31.0 |
| Access clarity | 50.0 |

**Agent readiness 53.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | — |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gitlab-ci/](https://apis.io/providers/gitlab-ci/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for GitLab CI/CD: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gitlab-ci/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
