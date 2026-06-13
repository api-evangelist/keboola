# Keboola

Keboola is a data operations platform providing a comprehensive REST API for managing data pipelines, storage buckets, transformations, configurations, orchestrations, and component jobs. The platform enables teams to build, automate, and scale data workflows across multiple cloud backends including Snowflake, BigQuery, and DuckDB, with support for 700+ data connectors.

## APIs

Keboola exposes 17 REST APIs covering the full data platform lifecycle:

- **Storage API** — Core data storage for buckets, tables, and files
- **Management API** — Projects, users, and organizational management
- **Queue API** — Job execution and pipeline orchestration
- **Scheduler API** — Time-based automation of pipeline runs
- **Developer Portal API** — Custom component creation and management
- **Encryption API** — Secrets and credential encryption
- **Notifications API** — Event subscriptions and alerts
- **OAuth Broker API** — Third-party OAuth authorization management
- **Stream API** — Real-time event ingestion into Storage
- **Query API** — Direct SQL execution on Snowflake and BigQuery
- **Sandboxes API** — Python/R workspace management
- **Vault API** — Variables and credentials store
- **Billing API** — Usage and payment management
- **AI API** — AI capability integrations
- **Importer API** — Streamlined bulk table imports
- **Editor API** — SQL editor session management
- **Synchronous Actions API** — Real-time component action triggers

## Authentication

All APIs use a Storage API token passed via the `X-StorageApi-Token` HTTP header.

## Links

- **Website:** https://www.keboola.com/
- **Developer Docs:** https://developers.keboola.com/
- **User Docs:** https://help.keboola.com/
- **API Portal:** https://api.keboola.com/
- **GitHub:** https://github.com/keboola
- **LinkedIn:** https://www.linkedin.com/company/keboola
- **Blog:** https://www.keboola.com/blog
- **Pricing:** https://www.keboola.com/business-solutions/pay-as-you-go-pricing
- **Status:** https://status.keboola.com/
- **X:** https://x.com/keboola

## SDKs and Tools

- **CLI:** https://developers.keboola.com/cli/
- **MCP Server:** https://github.com/keboola/mcp-server
- **Python SDK:** https://pypi.org/project/kbcstorage
- **Component Registry:** https://components.keboola.com/

## Maintainer

Kin Lane — kin@apievangelist.com
