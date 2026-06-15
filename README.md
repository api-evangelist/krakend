# KrakenD (krakend)

KrakenD is a stateless, distributed, high-performance open-source API gateway written in Go, focused on API aggregation, transformation, and security with a declarative configuration approach.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Aggregation
- API Gateway
- Go
- Open Source

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### KrakenD

KrakenD Community Edition is an ultra-high performance API gateway that aggregates multiple service calls into a single endpoint, transforming and filtering responses with a declarative JSON configuration.

- **Human URL:** [https://www.krakend.io/](https://www.krakend.io/)

#### Tags

- Aggregation
- API Gateway
- Go

#### Properties

- [Documentation](https://www.krakend.io/docs/overview/)
- [Getting Started](https://www.krakend.io/docs/overview/introduction/)
- [Reference](https://www.krakend.io/docs/configuration/structure/)
- [Changelog](https://github.com/krakend/krakend-ce/releases)
- [GitHub Repository](https://github.com/krakend/krakend-ce)
- [JSON Schema](json-schema/service-config.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/krakend-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Postman Collection](collections/krakend-service-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krakend-service-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KrakenD Service API

The KrakenD Service API exposes built-in operational endpoints on a running KrakenD gateway instance. It includes the health check endpoint at /__health (enabled by default), the debug endpoint at /__debug (enabled via configuration), and the extended metrics endpoint at /__stats for detailed runtime telemetry. These endpoints are used for monitoring, debugging, and health checking KrakenD deployments.

- **Human URL:** [https://www.krakend.io/docs/service-settings/health/](https://www.krakend.io/docs/service-settings/health/)
- **Base URL:** `http://localhost:8080`

#### Tags

- Health Check
- Monitoring
- Observability
- Operations

#### Properties

- [Documentation](https://www.krakend.io/docs/service-settings/health/)
- [Reference](https://www.krakend.io/docs/service-settings/debug-endpoint/)
- [OpenAPI](openapi/krakend-service-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/krakend-service-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krakend-service-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KrakenD Async Agent

The KrakenD Async Agent enables event-driven API consumption by connecting KrakenD to message brokers and event queues such as AMQP, Kafka, and NATS. It allows KrakenD to consume messages from topics and queues and forward them to backend services without requiring an inbound HTTP request from a client.

- **Human URL:** [https://www.krakend.io/docs/async/](https://www.krakend.io/docs/async/)

#### Tags

- Async
- Event-Driven
- Kafka
- Messaging

#### Properties

- [Documentation](https://www.krakend.io/docs/async/)
- [Reference](https://www.krakend.io/docs/async/amqp/)
- [JSON Schema](json-schema/async-agent.json) — [JSON Schema](https://json-schema.org/specification)
- [GitHub Repository](https://github.com/krakend/krakend-ce)
- [Postman Collection](collections/krakend-service-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/krakend-service-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/krakend)
- [Website](https://www.krakend.io/)
- [Documentation](https://www.krakend.io/docs/)
- [Getting Started](https://www.krakend.io/docs/overview/introduction/)
- [Blog](https://www.krakend.io/blog/)
- [Changelog](https://github.com/krakend/krakend-ce/releases)
- [GitHub Organization](https://github.com/krakend)
- [GitHub Repository](https://github.com/krakend/krakend-ce)
- [Community](https://community.krakend.io/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/krakend)
- [Issue  Tracker](https://github.com/krakend/krakend-ce/issues)
- [Developer  Tools](https://designer.krakend.io/)
- [JSON Schema](json-schema/service-config.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/krakend-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://www.krakend.io/partners/)
- [M C P Server](https://github.com/krakend/mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
