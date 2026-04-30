# dbt (dbt)

dbt Labs operates dbt Cloud, the managed platform for the open-source dbt (data build tool) used to transform data inside cloud warehouses. dbt Cloud exposes APIs for managing accounts, projects, jobs, and runs programmatically (Administrative API), inspecting project metadata (Discovery API), and querying governed metrics (Semantic Layer API).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Analytics Engineering, Data, ELT, Metrics, Projects, SQL, Transformation

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-28

## APIs

### dbt Cloud Administrative API

The dbt Cloud Administrative API manages accounts, projects, jobs, runs, environments, and other resources. It is the primary integration point for external orchestrators (Airflow, Dagster, Prefect) and for Terraform-based management of dbt Cloud configuration.

- **Base URL:** https://cloud.getdbt.com/api/v3
- **Human URL:** https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api)
- [OpenAPI](openapi/dbt-cloud-administrative-api-openapi.yml)
- [JSONSchema - Job](json-schema/dbt-job.json)
- [JSONSchema - Run](json-schema/dbt-run.json)
- [Rules](rules/dbt-cloud-administrative-api-rules.yml)
- [Capabilities](capabilities/dbt-cloud-administrative-api-capabilities.yml)

### dbt Cloud Discovery API

Every time dbt Cloud runs a project, it generates and stores information about the project. The Discovery API exposes that metadata - including details about models, sources, exposures, and execution results - so teams can understand and govern their DAG.

- **Base URL:** https://metadata.cloud.getdbt.com/graphql
- **Human URL:** https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api)
- [OpenAPI](openapi/dbt-cloud-discovery-api-openapi.yml)

### dbt Cloud Semantic Layer API

The dbt Semantic Layer lets teams define metrics in code with MetricFlow and query them consistently from BI tools, notebooks, and applications. The Semantic Layer API exposes metric and dimension queries via GraphQL, JDBC, and a Python SDK.

- **Base URL:** https://semantic-layer.cloud.getdbt.com/api/graphql
- **Human URL:** https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview)
- [OpenAPI](openapi/dbt-cloud-semantic-layer-api-openapi.yml)

## Common Properties

- [Website](https://www.getdbt.com/)
- [Documentation](https://docs.getdbt.com/)
- [Portal](https://docs.getdbt.com/docs/dbt-cloud-apis/overview)
- [Authentication](https://docs.getdbt.com/docs/dbt-cloud-apis/authentication)
- [Pricing](https://www.getdbt.com/pricing)
- [GitHub](https://github.com/dbt-labs/dbt-core)
- [JSON-LD](json-ld/dbt-context.jsonld)
- [Vocabulary](vocabulary/dbt-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
