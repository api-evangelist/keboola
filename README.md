# Keboola

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
