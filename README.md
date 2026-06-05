# dbt (dbt)

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
