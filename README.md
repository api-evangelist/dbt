# dbt

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

dbt Labs operates dbt Cloud, the managed platform for the open-source dbt (data build tool) used to transform data inside cloud warehouses. dbt Cloud exposes a set of APIs for managing accounts, projects, jobs, and runs programmatically (Administrative API), inspecting project metadata (Discovery API), and querying governed metrics (Semantic Layer API).

**Areas:** Analytics Engineering · Data · ELT · Metrics · Project · SQL · Transformation

## dbt on APIs.io

Everything profiled for dbt is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/dbt/](https://apis.io/providers/dbt/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [dbt Accounts API](https://apis.io/apis/dbt/dbt-accounts-api/) — The Accounts API from dbt — 1 operation(s) for accounts.
- [dbt Environments API](https://apis.io/apis/dbt/dbt-environments-api/) — The Environments API from dbt — 1 operation(s) for environments.
- [dbt Jobs API](https://apis.io/apis/dbt/dbt-jobs-api/) — The Jobs API from dbt — 1 operation(s) for jobs.
- [dbt Metadata API](https://apis.io/apis/dbt/dbt-metadata-api/) — The Metadata API from dbt — 1 operation(s) for metadata.
- [dbt Metrics API](https://apis.io/apis/dbt/dbt-metrics-api/) — The Metrics API from dbt — 1 operation(s) for metrics.
- [dbt Projects API](https://apis.io/apis/dbt/dbt-projects-api/) — The Projects API from dbt — 2 operation(s) for projects.
- [dbt Runs API](https://apis.io/apis/dbt/dbt-runs-api/) — The Runs API from dbt — 4 operation(s) for runs.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (13)

Multi-step workflows that chain operations into a business task.

- [dbt Cloud Account, Project and Job Inventory](https://apis.io/arazzos/dbt/dbt-account-project-job-inventory-workflow/)
- [dbt Cloud Bootstrap From Account to First Run](https://apis.io/arazzos/dbt/dbt-bootstrap-account-and-run-workflow/)
- [dbt Cloud Create Job and Run It](https://apis.io/arazzos/dbt/dbt-create-job-and-run-workflow/)
- [dbt Cloud Create, Run, Poll and Collect Artifacts](https://apis.io/arazzos/dbt/dbt-create-run-poll-artifacts-workflow/)
- [dbt Cloud Environment-Scoped Job Run](https://apis.io/arazzos/dbt/dbt-environment-job-run-workflow/)
- [dbt Cloud Find Job and Trigger Run](https://apis.io/arazzos/dbt/dbt-find-job-and-run-workflow/)
- [dbt Cloud Job Run History and Latest Artifacts](https://apis.io/arazzos/dbt/dbt-job-run-history-workflow/)
- [dbt Cloud Provision a Job in a Project Environment](https://apis.io/arazzos/dbt/dbt-provision-job-in-environment-workflow/)
- [dbt Cloud Re-run the Latest Failed Run](https://apis.io/arazzos/dbt/dbt-rerun-latest-failed-run-workflow/)
- [dbt Cloud Get Run and Fetch Its Artifacts](https://apis.io/arazzos/dbt/dbt-run-and-fetch-artifacts-workflow/)
- [dbt Cloud Run Completion to Metadata Discovery](https://apis.io/arazzos/dbt/dbt-run-metadata-discovery-workflow/)
- [dbt Cloud Run Completion to Semantic Layer Metrics](https://apis.io/arazzos/dbt/dbt-run-to-semantic-metrics-workflow/)
- [dbt Cloud Trigger Run and Poll to Completion](https://apis.io/arazzos/dbt/dbt-trigger-run-and-poll-workflow/)

#### GraphQL (1)

GraphQL schemas.

- [dbt GraphQL API](https://apis.io/graphqls/dbt/dbt-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Dbt Agentic Access](https://apis.io/agentic-access/dbt/dbt-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [dbt Cloud Job](https://apis.io/schemas/dbt/dbt-job/)
- [dbt Cloud Run](https://apis.io/schemas/dbt/dbt-run/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Dbt Context](https://apis.io/jsonld/dbt/dbt-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [dbt Cloud Vocabulary](https://apis.io/vocabularies/dbt/dbt-vocabulary/)

#### Collections (13)

Postman and Open Collection request collections.

- [dbt Cloud Administrative Accounts API](https://apis.io/collections/dbt/open-dbt-accounts-api/)
- [dbt Cloud Administrative API](https://apis.io/collections/dbt/open-dbt-cloud-administrative-api/)
- [dbt Cloud Discovery API](https://apis.io/collections/dbt/open-dbt-cloud-discovery-api/)
- [dbt Cloud Semantic Layer API](https://apis.io/collections/dbt/open-dbt-cloud-semantic-layer-api/)
- [dbt Cloud Administrative Accounts Environments API](https://apis.io/collections/dbt/open-dbt-environments-api/)
- [dbt Cloud Administrative Accounts Jobs API](https://apis.io/collections/dbt/open-dbt-jobs-api/)
- [dbt Cloud Administrative Accounts Metadata API](https://apis.io/collections/dbt/open-dbt-metadata-api/)
- [dbt Cloud Administrative Accounts Metrics API](https://apis.io/collections/dbt/open-dbt-metrics-api/)
- [dbt Cloud Administrative Accounts Projects API](https://apis.io/collections/dbt/open-dbt-projects-api/)
- [dbt Cloud Administrative Accounts Runs API](https://apis.io/collections/dbt/open-dbt-runs-api/)
- [dbt Cloud Administrative API](https://apis.io/collections/dbt/postman-dbt-cloud-administrative-api/)
- [dbt Cloud Discovery API](https://apis.io/collections/dbt/postman-dbt-cloud-discovery-api/)
- [dbt Cloud Semantic Layer API](https://apis.io/collections/dbt/postman-dbt-cloud-semantic-layer-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [dbt — cloud administrative api rules](https://apis.io/rules/dbt/dbt-cloud-administrative-api-rules/)
- [dbt — jsonschema rules](https://apis.io/rules/dbt/dbt-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Dbt Authentication](https://apis.io/security/dbt/dbt-authentication/)
- [Dbt Domain Security](https://apis.io/security/dbt/dbt-domain-security/)
- [Dbt Trust Center](https://apis.io/security/dbt/dbt-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Dbt Plans Pricing](https://apis.io/plans/dbt/dbt-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Dbt Rate Limits](https://apis.io/rate-limits/dbt/dbt-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Dbt Finops](https://apis.io/finops/dbt/dbt-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.getdbt.com/)
- [Documentation](https://docs.getdbt.com/)
- [Pricing](https://www.getdbt.com/pricing)
- [Blog](https://docs.getdbt.com/blog)
- [Terms of service](https://www.getdbt.com/cloud/terms)
- [Privacy policy](https://www.getdbt.com/cloud/privacy-policy)

## API Evangelist rating

**Kin Score 45.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 55.1 |
| Contract governance | 27.3 |
| Operational transparency | 13.2 |
| Developer ergonomics | 41.7 |
| Access clarity | 47.4 |

**Agent readiness 19.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/dbt/](https://apis.io/providers/dbt/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for dbt: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/dbt/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
