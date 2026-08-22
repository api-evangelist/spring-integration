# Spring Integration (spring-integration)

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

Spring Integration extends the Spring programming model to support enterprise integration patterns (EIP), providing lightweight messaging within Spring-based applications and integration with external systems via declarative adapters. It supports message channels, filters, transformers, routers, aggregators, and a wide range of inbound/outbound adapters for HTTP, JMS, AMQP, TCP, FTP, JDBC, email, and many more.

**APIs.json:** [https://spring.io/projects/spring-integration](https://spring.io/projects/spring-integration)

## Scope

- **Type:** Index

## Tags

- AMQP
- Enterprise Integration
- Event-Driven
- Integration Patterns
- Java
- Messaging
- Spring

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Spring Integration HTTP Adapter API

HTTP inbound and outbound channel adapters for Spring Integration. Provides HTTP request-response messaging, REST template integration, and configurable URL mapping for inbound HTTP gateways.

- **Human URL:** [https://docs.spring.io/spring-integration/docs/current/reference/html/http.html](https://docs.spring.io/spring-integration/docs/current/reference/html/http.html)
- **Base URL:** `http://localhost:8080`

#### Tags

- HTTP
- Inbound
- Messaging
- Outbound
- REST

#### Properties

- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/http.html)
- [GitHub Repository](https://github.com/spring-projects/spring-integration)
- [OpenAPI](openapi/spring-integration-http-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-integration-http.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-integration-http.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Integration Management API

Management and monitoring REST API for Spring Integration. Exposes channel statistics, handler metrics, component lifecycle control (start/stop), and message history configuration via HTTP endpoints.

- **Human URL:** [https://docs.spring.io/spring-integration/docs/current/reference/html/management.html](https://docs.spring.io/spring-integration/docs/current/reference/html/management.html)
- **Base URL:** `http://localhost:8080/api`

#### Tags

- Management
- Messaging
- Metrics
- Monitoring

#### Properties

- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/management.html)
- [OpenAPI](openapi/spring-integration-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-integration-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-integration-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Integration AMQP Adapter

AMQP channel adapters and gateways for Spring Integration. Provides RabbitMQ message-driven and polling inbound adapters, outbound channel adapters, and request/reply gateways.

- **Human URL:** [https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html](https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html)

#### Tags

- AMQP
- Messaging
- RabbitMQ

#### Properties

- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.integration/spring-integration-amqp)
- [Postman Collection](collections/spring-integration-http.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-integration-http.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-integration-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-integration-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Integration Kafka Adapter

Kafka channel adapters for Spring Integration. Provides message-driven inbound adapters, outbound channel adapters, and request/reply gateways for Apache Kafka integration.

- **Human URL:** [https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html](https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html)

#### Tags

- Event Streaming
- Kafka
- Messaging

#### Properties

- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.integration/spring-integration-kafka)
- [Postman Collection](collections/spring-integration-http.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-integration-http.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/spring-integration-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-integration-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spring.io/projects/spring-integration)
- [Documentation](https://docs.spring.io/spring-integration/reference/)
- [GitHub Organization](https://github.com/spring-projects/spring-integration)
- [Getting Started](https://spring.io/guides/gs/integration)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-integration)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.integration)
- [Releases](https://github.com/spring-projects/spring-integration/releases)
- [Blog](https://spring.io/blog/category/integration)
- [Sample  Projects](https://github.com/spring-projects/spring-integration-samples)

## Maintainers

**FN:** Spring Team
**Email:** spring-projects@vmware.com
**URL:** https://spring.io/team
