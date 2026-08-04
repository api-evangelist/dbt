# dbt (dbt)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

dbt Labs operates dbt Cloud, the managed platform for the open-source dbt (data build tool) used to transform data inside cloud warehouses. dbt Cloud exposes a set of APIs for managing accounts, projects, jobs, and runs programmatically (Administrative API), inspecting project metadata (Discovery API), and querying governed metrics (Semantic Layer API).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Analytics Engineering
- Data
- ELT
- Metrics
- Projects
- SQL
- Transformation

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### dbt Cloud Administrative API

The dbt Cloud Administrative API manages accounts, projects, jobs, runs, environments, and other resources. It is the primary integration point for external orchestrators (Airflow, Dagster, Prefect) and for Terraform-based management of dbt Cloud configuration.

- **Human URL:** [https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api](https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api)
- **Base URL:** `https://cloud.getdbt.com/api/v3`

#### Tags

- Accounts
- Administration
- Jobs
- Projects
- Runs

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api)
- [OpenAPI](openapi/dbt-cloud-administrative-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbt-cloud-administrative-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbt-cloud-administrative-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/dbt-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dbt-run.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/dbt-cloud-administrative-api-rules.yml)
- [Capabilities](capabilities/dbt-cloud-administrative-api-capabilities.yml)

### dbt Cloud Discovery API

Every time dbt Cloud runs a project, it generates and stores information about the project. The Discovery API exposes that metadata including details about models, sources, exposures, and execution results so teams can understand and govern their DAG.

- **Human URL:** [https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api](https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api)
- **Base URL:** `https://metadata.cloud.getdbt.com/graphql`

#### Tags

- Discovery
- GraphQL
- Lineage
- Metadata

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api)
- [OpenAPI](openapi/dbt-cloud-discovery-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbt-cloud-discovery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbt-cloud-discovery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### dbt Cloud Semantic Layer API

The dbt Semantic Layer lets teams define metrics in code with MetricFlow and query them consistently from BI tools, notebooks, and applications. The Semantic Layer API exposes metric and dimension queries via GraphQL, JDBC, and a Python SDK.

- **Human URL:** [https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview)
- **Base URL:** `https://semantic-layer.cloud.getdbt.com/api/graphql`

#### Tags

- Dimensions
- GraphQL
- JDBC
- MetricFlow
- Metrics
- Semantic Layer

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview)
- [OpenAPI](openapi/dbt-cloud-semantic-layer-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbt-cloud-semantic-layer-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbt-cloud-semantic-layer-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/dbtlabs)
- [Website](https://www.getdbt.com/)
- [Documentation](https://docs.getdbt.com/)
- [Portal](https://docs.getdbt.com/docs/dbt-cloud-apis/overview)
- [Authentication](https://docs.getdbt.com/docs/dbt-cloud-apis/authentication)
- [Pricing](https://www.getdbt.com/pricing)
- [Git Hub](https://github.com/dbt-labs/dbt-core)
- [SDK](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-python)
- [Terms of Service](https://www.getdbt.com/cloud/terms)
- [Privacy Policy](https://www.getdbt.com/cloud/privacy-policy)
- [JSON-LD](json-ld/dbt-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/dbt-vocabulary.yml)
- [Integrations](https://www.getdbt.com/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
