# Boltic (boltic)

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
