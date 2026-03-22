# KrakenD (krakend)
KrakenD is a stateless, distributed, high-performance open-source API gateway written in Go, focused on API aggregation, transformation, and security with a declarative configuration approach.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - API Gateway, Go, Open Source, Aggregation

## Timestamps

- **Created:** 2026-03-18 
- **Modified:** 2026-03-18 

## APIs

### KrakenD
KrakenD Community Edition is an ultra-high performance API gateway that aggregates multiple service calls into a single endpoint, transforming and filtering responses with a declarative JSON configuration.

**Human URL:** [https://www.krakend.io/](https://www.krakend.io/)


#### Tags:

 - API Gateway, Go, Aggregation

#### Properties

- [Documentation](https://www.krakend.io/docs/overview/)
- [Getting Started](https://www.krakend.io/docs/overview/introduction/)
- [Reference](https://www.krakend.io/docs/configuration/structure/)
- [Change Log](https://github.com/krakend/krakend-ce/releases)
- [GitHubRepository](https://github.com/krakend/krakend-ce)
- [JSONSchema](json-schema/service-config.json)
- [JSON-LD](json-ld/krakend-context.jsonld)

### KrakenD Service API
The KrakenD Service API exposes built-in operational endpoints on a running KrakenD gateway instance. It includes the health check endpoint at /__health (enabled by default), the debug endpoint at /__debug (enabled via configuration), and the extended metrics endpoint at /__stats for detailed runtime telemetry. These endpoints are used for monitoring, debugging, and health checking KrakenD deployments.

**Human URL:** [https://www.krakend.io/docs/service-settings/health/](https://www.krakend.io/docs/service-settings/health/)


#### Tags:

 - Health Check, Observability, Monitoring, Operations

#### Properties

- [Documentation](https://www.krakend.io/docs/service-settings/health/)
- [Reference](https://www.krakend.io/docs/service-settings/debug-endpoint/)
- [OpenAPI](openapi/krakend-service-api-openapi.yml)

### KrakenD Async Agent
The KrakenD Async Agent enables event-driven API consumption by connecting KrakenD to message brokers and event queues such as AMQP, Kafka, and NATS. It allows KrakenD to consume messages from topics and queues and forward them to backend services without requiring an inbound HTTP request from a client.

**Human URL:** [https://www.krakend.io/docs/async/](https://www.krakend.io/docs/async/)


#### Tags:

 - Async, Event-Driven, Messaging, Kafka

#### Properties

- [Documentation](https://www.krakend.io/docs/async/)
- [Reference](https://www.krakend.io/docs/async/amqp/)
- [JSONSchema](json-schema/async-agent.json)
- [GitHubRepository](https://github.com/krakend/krakend-ce)

## Common Properties

- [Website](https://www.krakend.io/)
- [Documentation](https://www.krakend.io/docs/)
- [Getting Started](https://www.krakend.io/docs/overview/introduction/)
- [Blog](https://www.krakend.io/blog/)
- [Change Log](https://github.com/krakend/krakend-ce/releases)
- [GitHub Organization](https://github.com/krakend)
- [GitHubRepository](https://github.com/krakend/krakend-ce)
- [Community](https://community.krakend.io/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/krakend)
- [Issue Tracker](https://github.com/krakend/krakend-ce/issues)
- [Developer Tools](https://designer.krakend.io/)
- [JSONSchema](json-schema/service-config.json)
- [JSON-LD](json-ld/krakend-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
