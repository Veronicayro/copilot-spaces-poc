# Enterprise Architecture Patterns

## Transactional Outbox

Purpose

Guarantee consistency between database transactions and event publication.

Problem solved

Avoid the dual-write problem where a database transaction succeeds but event publication fails.

Advantages

- Reliable event delivery
- No distributed transactions
- Eventual consistency

---

## Circuit Breaker

Purpose

Protect integrations from cascading failures.

States

- Closed
- Open
- Half Open

Typical configuration

Failure threshold

5 failures

Reset timeout

60 seconds

---

## API Gateway

Responsibilities

- Authentication
- Routing
- Rate limiting
- Logging

Does not contain business logic.

---

## Event Driven Architecture

Characteristics

- Asynchronous communication
- Loose coupling
- High scalability

Technologies

Kafka

RabbitMQ

Azure Service Bus
