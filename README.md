# Spring Integration

Spring Integration extends the Spring programming model to support enterprise integration patterns (EIP), providing lightweight messaging within Spring-based applications and integration with external systems via declarative adapters. It supports message channels, filters, transformers, routers, aggregators, and a wide range of adapters for HTTP, JMS, AMQP, TCP, FTP, JDBC, email, and many more.

**URL:** https://spring.io/projects/spring-integration

## Tags

AMQP, Enterprise Integration, Event-Driven, Integration Patterns, Java, Messaging, Spring

## APIs

### Spring Integration HTTP Adapter API

HTTP inbound and outbound channel adapters for Spring Integration. Provides HTTP request-response messaging, REST template integration, and configurable URL mapping for inbound HTTP gateways.

**Human URL:** https://docs.spring.io/spring-integration/docs/current/reference/html/http.html
**Base URL:** http://localhost:8080

**Tags:** HTTP, Inbound, Messaging, Outbound, REST

**Properties:**
- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/http.html)
- [GitHub Repository](https://github.com/spring-projects/spring-integration)
- [OpenAPI](openapi/spring-integration-http-openapi.yml)

### Spring Integration Management API

Management and monitoring REST API for Spring Integration. Exposes channel statistics, handler metrics, adapter lifecycle control, and integration flow graph visualization.

**Human URL:** https://docs.spring.io/spring-integration/docs/current/reference/html/management.html
**Base URL:** http://localhost:8080/api

**Tags:** Management, Messaging, Metrics, Monitoring

**Properties:**
- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/management.html)
- [OpenAPI](openapi/spring-integration-management-openapi.yml)
- [JSON Schema](json-schema/spring-integration-message-schema.json)
- [JSON Structure](json-structure/spring-integration-channel-structure.json)

### Spring Integration AMQP Adapter

AMQP channel adapters and gateways for Spring Integration. Provides RabbitMQ message-driven and polling inbound adapters, outbound channel adapters, and request/reply gateways.

**Human URL:** https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html

**Tags:** AMQP, Messaging, RabbitMQ

**Properties:**
- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.integration/spring-integration-amqp)

### Spring Integration Kafka Adapter

Kafka channel adapters for Spring Integration. Provides message-driven inbound adapters, outbound channel adapters, and request/reply gateways for Apache Kafka integration.

**Human URL:** https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html

**Tags:** Event Streaming, Kafka, Messaging

**Properties:**
- [Documentation](https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.integration/spring-integration-kafka)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-integration-management-openapi.yml](openapi/spring-integration-management-openapi.yml) | Spring Integration management and monitoring REST API |
| [spring-integration-http-openapi.yml](openapi/spring-integration-http-openapi.yml) | Spring Integration HTTP inbound gateway API |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-integration-message-schema.json](json-schema/spring-integration-message-schema.json) | Spring Integration message, headers, and channel statistics schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-integration-channel-structure.json](json-structure/spring-integration-channel-structure.json) | Channel statistics, handler metrics, and integration graph structure |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-integration-context.jsonld](json-ld/spring-integration-context.jsonld) | Spring Integration and EIP linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-integration-get-graph-example.json](examples/spring-integration-get-graph-example.json) | Integration flow graph response example |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-integration-rules.yml](rules/spring-integration-rules.yml) | API design rules for Spring Integration conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/integration-monitoring.yaml](capabilities/integration-monitoring.yaml) | Integration monitoring workflow (channels, handlers, adapters, graph) |
| [capabilities/shared/spring-integration-management.yaml](capabilities/shared/spring-integration-management.yaml) | Shared Spring Integration management consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-integration-vocabulary.yml](vocabulary/spring-integration-vocabulary.yml) | Spring Integration and EIP domain vocabulary |

## Common Properties

- [Website](https://spring.io/projects/spring-integration)
- [Documentation](https://docs.spring.io/spring-integration/reference/)
- [GitHub Organization](https://github.com/spring-projects/spring-integration)
- [Getting Started](https://spring.io/guides/gs/integration)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-integration)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.integration)
- [Releases](https://github.com/spring-projects/spring-integration/releases)
- [Blog](https://spring.io/blog/category/integration)
- [Sample Projects](https://github.com/spring-projects/spring-integration-samples)

## Maintainers

**Name:** Spring Team  
**Email:** spring-projects@vmware.com  
**URL:** https://spring.io/team
