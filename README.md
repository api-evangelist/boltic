# Boltic (boltic)

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

Boltic is an AI workflow automation platform that helps businesses streamline operations across customer support, finance, product, and marketing functions. The platform enables companies to build autonomous AI agents, create no-code workflows with drag-and-drop functionality, and connect with over 500 integrations including major tools like Salesforce, HubSpot, Shopify, and Google BigQuery.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Automation
- DataSync
- Gateways
- NoCode
- Streaming
- Workflows

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-05-19

## APIs

### Boltic Gateway API

The Boltic Gateway API provides a developer-friendly API gateway designed to simplify and secure how services interact across your platform. It enables seamless request routing, payload transformation, and enforcement of security policies across diverse integration types including serverless functions, workflows, tables, and proxy endpoints. The Gateway supports dynamic URL rewriting, path parameter injection, fine-grained authentication, and real-time observability.

- **Human URL:** [https://docs.boltic.io/gateway/intro/](https://docs.boltic.io/gateway/intro/)

#### Tags

- Gateways
- Plugins
- Routing
- Security

#### Properties

- [Documentation](https://docs.boltic.io/gateway/intro/)
- [OpenAPI](openapi/boltic-gateway-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boltic-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boltic-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/boltic-route.json) — [JSON Schema](https://json-schema.org/specification)

### Boltic Workflow API

The Boltic Workflow API enables programmatic creation, management, and execution of automation workflows. Workflows are visual, no-code automation sequences that connect triggers with actions across 500+ integrations. The API supports HTTP-triggered workflows with customizable responses, scheduled executions, webhook-based triggers, and integration with AI providers including Perplexity, Hugging Face, Meta, and DeepSeek.

- **Human URL:** [https://www.boltic.io/products/workflow](https://www.boltic.io/products/workflow)

#### Tags

- Automation
- Integrations
- Triggers
- Workflows

#### Properties

- [Documentation](https://docs.boltic.io/)
- [OpenAPI](openapi/boltic-workflow-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boltic-workflow-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boltic-workflow-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/boltic-workflow.json) — [JSON Schema](https://json-schema.org/specification)

### Boltic Tables API

The Boltic Tables API provides programmatic access to Boltic Tables, a no-code database for teams to organize, manage, and automate structured data workflows. The API supports full CRUD operations on tables and rows, SQL query execution via a built-in SQL editor with AI-powered query generation, and integration with workflows for automated data processing triggered by table changes.

- **Human URL:** [https://www.boltic.io/products/boltic-tables](https://www.boltic.io/products/boltic-tables)

#### Tags

- CRUD
- Databases
- NoCode
- Tables

#### Properties

- [Documentation](https://docs.boltic.io/docs/workflow-builder/activities/tables/)
- [OpenAPI](openapi/boltic-tables-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boltic-tables-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boltic-tables-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/boltic-table.json) — [JSON Schema](https://json-schema.org/specification)

### Boltic Pipes API

The Boltic Pipes API provides programmatic access to data synchronization pipelines that connect data sources to destinations. Pipes enable real-time data syncing across systems via automated pipelines with zero maintenance. Sources include databases such as MongoDB, MySQL, and PostgreSQL, SaaS applications via API endpoints, and file storage. The API supports configurable sync frequencies including minutely, hourly, and daily schedules.

- **Human URL:** [https://docs.boltic.io/docs/pipes/pipe-creation/](https://docs.boltic.io/docs/pipes/pipe-creation/)

#### Tags

- DataSync
- ETL
- Integration
- Pipelines

#### Properties

- [Documentation](https://docs.boltic.io/docs/pipes/pipe-creation/)
- [OpenAPI](openapi/boltic-pipes-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boltic-pipes-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boltic-pipes-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/boltic-pipe.json) — [JSON Schema](https://json-schema.org/specification)

### Boltic Streams API

The Boltic Streams API provides real-time event streaming capabilities for tracking custom events and streaming data from websites, mobile apps, and servers. It includes source debugger tools for confirming API call delivery, an event analysis dashboard for monitoring event flows, and real-time data processing for actionable insights.

- **Human URL:** [https://www.boltic.io/products/streams](https://www.boltic.io/products/streams)

#### Tags

- Analytics
- Events
- RealTime
- Streaming

#### Properties

- [Documentation](https://docs.boltic.io/docs/streams/intro/)
- [OpenAPI](openapi/boltic-streams-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boltic-streams-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boltic-streams-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/boltic-stream-event.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [GitHub Organization](https://github.com/bolticio)
- [LinkedIn](https://www.linkedin.com/company/officialboltic)
- [Website](https://www.boltic.io/)
- [Documentation](https://docs.boltic.io/)
- [Templates](https://www.boltic.io/templates)
- [Integrations](https://www.boltic.io/integrations)
- [Pricing](https://www.boltic.io/pricing)
- [About](https://www.boltic.io/about-us)
- [Partners](https://www.boltic.io/partners)
- [Blog](https://www.boltic.io/blog)
- [Changelog](https://www.boltic.io/changelog)
- [J S O N L D Context](json-ld/boltic-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
