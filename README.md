# KrakenD (krakend)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
