# Boltic (boltic)
Boltic is an AI workflow automation platform that helps businesses streamline operations across customer support, finance, product, and marketing functions. The platform enables companies to build autonomous AI agents, create no-code workflows with drag-and-drop functionality, and connect with over 500 integrations including major tools like Salesforce, HubSpot, Shopify, and Google BigQuery. Boltic offers a comprehensive suite of features including an API gateway for service routing and security, serverless computing, real-time data syncing through pipes, event streaming, built-in databases for structured data management, and MCP servers for live AI context and actions. With support for leading AI providers like Perplexity, Hugging Face, Meta, and DeepSeek, the platform has executed over 474 million workflows with 99% agentic accuracy, particularly serving industries like retail and e-commerce, healthcare, financial services, and B2B. The platform is enterprise-ready with SOC 2 Type II certification, GDPR compliance, multi-region servers, and a strict policy of never training AI models on customer data.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Workflows, Automation, Gateways, DataSync, Streaming, NoCode

## Timestamps

- **Created:** 2026-01-02 
- **Modified:** 2026-03-14 

## APIs

### Boltic Gateway API
The Boltic Gateway API provides a developer-friendly API gateway designed to simplify and secure how services interact across your platform. It enables seamless request routing, payload transformation, and enforcement of security policies across diverse integration types including serverless functions, workflows, tables, and proxy endpoints. The Gateway supports dynamic URL rewriting, path parameter injection, fine-grained authentication, and real-time observability.

**Human URL:** [https://docs.boltic.io/gateway/intro/](https://docs.boltic.io/gateway/intro/)


#### Tags:

 - Gateways, Routing, Security, Plugins

#### Properties

- [Documentation](https://docs.boltic.io/gateway/intro/)
- [OpenAPI](openapi/boltic-gateway-api-openapi.yml)
- [JSONSchema](json-schema/boltic-route.json)

### Boltic Workflow API
The Boltic Workflow API enables programmatic creation, management, and execution of automation workflows. Workflows are visual, no-code automation sequences that connect triggers with actions across 500+ integrations. The API supports HTTP-triggered workflows with customizable responses, scheduled executions, webhook-based triggers, and integration with AI providers including Perplexity, Hugging Face, Meta, and DeepSeek.

**Human URL:** [https://www.boltic.io/products/workflow](https://www.boltic.io/products/workflow)


#### Tags:

 - Workflows, Automation, Triggers, Integrations

#### Properties

- [Documentation](https://docs.boltic.io/)
- [OpenAPI](openapi/boltic-workflow-api-openapi.yml)
- [JSONSchema](json-schema/boltic-workflow.json)

### Boltic Tables API
The Boltic Tables API provides programmatic access to Boltic Tables, a no-code database for teams to organize, manage, and automate structured data workflows. The API supports full CRUD operations on tables and rows, SQL query execution via a built-in SQL editor with AI-powered query generation, and integration with workflows for automated data processing triggered by table changes.

**Human URL:** [https://www.boltic.io/products/boltic-tables](https://www.boltic.io/products/boltic-tables)


#### Tags:

 - Databases, Tables, CRUD, NoCode

#### Properties

- [Documentation](https://docs.boltic.io/docs/workflow-builder/activities/tables/)
- [OpenAPI](openapi/boltic-tables-api-openapi.yml)
- [JSONSchema](json-schema/boltic-table.json)

### Boltic Pipes API
The Boltic Pipes API provides programmatic access to data synchronization pipelines that connect data sources to destinations. Pipes enable real-time data syncing across systems via automated pipelines with zero maintenance. Sources include databases such as MongoDB, MySQL, and PostgreSQL, SaaS applications via API endpoints, and file storage. The API supports configurable sync frequencies including minutely, hourly, and daily schedules.

**Human URL:** [https://docs.boltic.io/docs/pipes/pipe-creation/](https://docs.boltic.io/docs/pipes/pipe-creation/)


#### Tags:

 - DataSync, Pipelines, ETL, Integration

#### Properties

- [Documentation](https://docs.boltic.io/docs/pipes/pipe-creation/)
- [OpenAPI](openapi/boltic-pipes-api-openapi.yml)
- [JSONSchema](json-schema/boltic-pipe.json)

### Boltic Streams API
The Boltic Streams API provides real-time event streaming capabilities for tracking custom events and streaming data from websites, mobile apps, and servers. It includes source debugger tools for confirming API call delivery, an event analysis dashboard for monitoring event flows, and real-time data processing for actionable insights.

**Human URL:** [https://www.boltic.io/products/streams](https://www.boltic.io/products/streams)


#### Tags:

 - Streaming, Events, RealTime, Analytics

#### Properties

- [Documentation](https://docs.boltic.io/docs/streams/intro/)
- [OpenAPI](openapi/boltic-streams-api-openapi.yml)
- [JSONSchema](json-schema/boltic-stream-event.json)

## Common Properties

- [Website](https://www.boltic.io/)
- [Documentation](https://docs.boltic.io/)
- [Templates](https://www.boltic.io/templates)
- [Integrations](https://www.boltic.io/integrations)
- [Pricing](https://www.boltic.io/pricing)
- [About](https://www.boltic.io/about-us)
- [Partners](https://www.boltic.io/partners)
- [Blog](https://www.boltic.io/blog)
- [ChangeLog](https://www.boltic.io/changelog)
- [JSONLDContext](json-ld/boltic-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
