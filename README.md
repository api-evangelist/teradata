# Teradata (teradata)
Teradata provides enterprise analytics and data management solutions. The Teradata VantageCloud platform delivers connected multi-cloud data analytics with capabilities for data warehousing, advanced analytics, and machine learning at scale. Teradata offers REST APIs for managing QueryGrid data fabric connections, running SQL queries, and administering platform resources.

**URL:** [Visit APIs.json URL](https://www.teradata.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Cloud, Data Management, Data Warehousing, Database, Enterprise, Machine Learning, SQL

## Timestamps

- **Created:** 2026-04-18
- **Modified:** 2026-04-18

## APIs

### Teradata QueryGrid Manager API
REST API for centralized administration and monitoring of Teradata QueryGrid, the data fabric that enables seamless cross-system analytics. Manage data centers, systems, bridges, connectors, links, fabrics, networks, and node configurations. Perform diagnostic checks, software installations, and query monitoring across connected systems.

**Human URL:** [https://github.com/Teradata/querygrid-apidocs](https://github.com/Teradata/querygrid-apidocs)

#### Tags:

 - Configuration, Data Fabric, Diagnostics, Monitoring, QueryGrid

#### Properties

- [Documentation](https://github.com/Teradata/querygrid-apidocs)
- [OpenAPI](openapi/teradata-querygrid-manager-api.yaml)

### Teradata Query Service API
REST API for executing SQL queries against Teradata Vantage systems. Provides HTTP-based access to run queries, retrieve results, and manage sessions for application integration and browser-based query tools.

**Human URL:** [https://docs.teradata.com](https://docs.teradata.com)

#### Tags:

 - Query, REST, SQL, Vantage

#### Properties

- [Documentation](https://docs.teradata.com)
- [OpenAPI](openapi/teradata-query-service-api.yaml)

## Common Properties

- [Portal](https://developer.teradata.com)
- [Documentation](https://docs.teradata.com)
- [GettingStarted](https://quickstarts.teradata.com)
- [GitHubOrganization](https://github.com/Teradata)
- [Support](https://support.teradata.com)
- [Blog](https://www.teradata.com/blog)
- [Training](https://www.teradata.com/University)
- [TermsOfService](https://www.teradata.com/Legal/Terms-of-Use)
- [PrivacyPolicy](https://www.teradata.com/Legal/Privacy)
- [Python SQL Driver SDK](https://pypi.org/project/teradatasql/)
- [Node.js SQL Driver SDK](https://www.npmjs.com/package/teradatasql)
- [R SQL Driver SDK](https://github.com/Teradata/r-driver)
- [Rust API SDK](https://github.com/Teradata/teradatarustapi)
- [Go SQL Driver SDK](https://github.com/Teradata/gosql-driver)
- [JDBC Driver SDK](https://github.com/Teradata/jdbc-driver)
- [VS Code SQL Extension CLI](https://github.com/Teradata/teradata-vscode-sql-extension)
- [MCP Server](https://github.com/Teradata/teradata-mcp-server)
- [QueryGrid MCP Server](https://github.com/Teradata/teradata-qg-mcp-server)

## Features

| Name | Description |
|------|-------------|
| VantageCloud | Cloud-native analytics platform available on AWS, Azure, and Google Cloud. |
| ClearScape Analytics | Advanced analytics engine with machine learning, graph analytics, and AI capabilities built into Vantage. |
| QueryGrid | Data fabric for multi-system analytics enabling queries across Teradata, Hadoop, Spark, and cloud object storage. |
| ModelOps | Model lifecycle management for deploying, monitoring, and governing machine learning models. |
| AI Unlimited | On-demand AI and ML engine for exploratory analytics without infrastructure management. |
| Open Table Formats | Support for Apache Iceberg and open table formats for lakehouse analytics. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Data Warehousing | Centralized data warehousing with petabyte-scale analytics for enterprise reporting and BI. |
| Advanced Analytics | In-database machine learning, statistical analysis, and predictive modeling at scale. |
| Multi-Cloud Analytics | Connected analytics across AWS, Azure, and Google Cloud with data fabric integration. |
| AI and ML Operations | End-to-end machine learning model lifecycle management with ModelOps. |
| Real-Time Data Integration | Real-time data ingestion and analytics with QueryGrid cross-system query federation. |

## Integrations

| Name | Description |
|------|-------------|
| dbt | dbt adapter for Teradata Vantage enabling data transformations using dbt workflows. |
| Apache Airflow | Airflow provider for orchestrating Teradata data pipeline workflows. |
| Dagster | Dagster integration for Teradata data orchestration and observability. |
| Airbyte | Airbyte connector for ELT data pipelines to and from Teradata. |
| Fivetran | Fivetran destination connector for automated data loading into Teradata. |
| MuleSoft | MuleSoft connector for integrating Teradata with enterprise application networks. |
| Dataiku | Dataiku plugin for running analytics within the Teradata Vantage environment. |
| LangChain | LangChain integration for using Teradata as a vector store and data source in AI applications. |
| Apache Iceberg | Teradata support for Apache Iceberg open table format for lakehouse analytics. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Teradata QueryGrid Manager API](openapi/teradata-querygrid-manager-api.yaml)
- [Teradata Query Service API](openapi/teradata-query-service-api.yaml)

### JSON Schema

- [ApiInfo](json-schema/querygrid-manager-api-api-info-schema.json)
- [Issue](json-schema/querygrid-manager-api-issue-schema.json)
- [Node](json-schema/querygrid-manager-api-node-schema.json)
- [System](json-schema/querygrid-manager-api-system-schema.json)
- [DataCenter](json-schema/querygrid-manager-api-data-center-schema.json)
- [Bridge](json-schema/querygrid-manager-api-bridge-schema.json)
- [Connector](json-schema/querygrid-manager-api-connector-schema.json)
- [Session](json-schema/query-service-api-session-schema.json)
- [QueryResult](json-schema/query-service-api-query-result-schema.json)

### JSON Structure

- [System](json-structure/querygrid-manager-api-system-structure.json)
- [Node](json-structure/querygrid-manager-api-node-structure.json)
- [Issue](json-structure/querygrid-manager-api-issue-structure.json)
- [Session](json-structure/query-service-api-session-structure.json)
- [QueryResult](json-structure/query-service-api-query-result-structure.json)

### JSON-LD

- [QueryGrid Manager API Context](json-ld/teradata-querygrid-manager-api-context.jsonld)
- [Query Service API Context](json-ld/teradata-query-service-api-context.jsonld)

### Examples

- [System](examples/querygrid-manager-api-system-example.json)
- [Node](examples/querygrid-manager-api-node-example.json)
- [Issue](examples/querygrid-manager-api-issue-example.json)
- [Session](examples/query-service-api-session-example.json)
- [QueryResult](examples/query-service-api-query-result-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [QueryGrid Manager](capabilities/shared/querygrid-manager.yaml) -- 14 operations for data fabric administration
- [Query Service](capabilities/shared/query-service.yaml) -- 6 operations for SQL query execution

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Fabric Management](capabilities/data-fabric-management.yaml) | QueryGrid Manager + Query Service | 7 | Data Engineer |
| [Query and Analytics](capabilities/query-and-analytics.yaml) | Query Service + QueryGrid Manager | 5 | Data Analyst |

## Vocabulary

- [Teradata Vocabulary](vocabulary/teradata-vocabulary.yaml) -- Unified taxonomy mapping 11 resources, 6 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Teradata Spectral Rules](rules/teradata-spectral-rules.yml) -- 28 rules across 10 categories enforcing Teradata API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
