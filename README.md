# Axon Framework

Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed systems.

## APIs

### Axon Framework (Axon Server API)
Management API for Axon Server applications, contexts, and administration.
- **Documentation**: https://docs.axoniq.io/
- **OpenAPI**: [openapi/axon-server-api.yml](openapi/axon-server-api.yml) (20 operations)

## Artifacts

| Directory | Contents |
|---|---|
| [openapi/](openapi/) | 1 OpenAPI specification (20 operations) |
| [json-schema/](json-schema/) | 10 JSON Schema files |
| [json-structure/](json-structure/) | 10 JSON Structure files |
| [json-ld/](json-ld/) | 1 JSON-LD context file |
| [examples/](examples/) | 10 example files |
| [rules/](rules/) | Spectral ruleset |
| [capabilities/](capabilities/) | Naftiko capability definitions |
| [vocabulary/](vocabulary/) | Domain vocabulary |

## Features

- **CQRS Pattern** — Separate command and query models for scalable, maintainable architecture.
- **Event Sourcing** — Store application state as a sequence of events for full audit trail.
- **Domain-Driven Design** — First-class support for aggregates, sagas, and bounded contexts.
- **Axon Server Integration** — Zero-configuration event store and message router.
- **Distributed Systems Support** — Built-in routing for commands, events, and queries.
- **Spring Boot Integration** — Seamless Spring Boot auto-configuration.
- **Testing Support** — Built-in testing fixtures for validating aggregate behavior.
- **Saga Management** — Manage long-running business processes with durable saga state.

## Use Cases

- **Microservices Architecture** — Build event-driven microservices with reliable message routing.
- **Audit Trail** — Maintain complete audit trails by storing all state changes as events.
- **Temporal Queries** — Reconstruct system state at any point in time from the event store.
- **Collaborative Domains** — Build complex collaborative domains with CQRS separation.
- **Workflow Automation** — Automate multi-step business workflows with event-driven sagas.

## Links

- **Website**: https://www.axoniq.io/
- **Documentation**: https://docs.axoniq.io/
- **Getting Started**: https://docs.axoniq.io/axon-framework/getting-started
- **Pricing**: https://www.axoniq.io/pricing
- **Blog**: https://www.axoniq.io/blog
- **GitHub**: https://github.com/AxonFramework/AxonFramework
- **Status**: https://status.axoniq.io/

## Maintainers

- **Kin Lane** — kin@apievangelist.com
