# Enterprise Architecture Governance

## General Principles

Business APIs orchestrate business capabilities.

Domain APIs own business logic.

Support APIs provide reusable technical services.

Experience APIs expose capabilities to consumers.

---

## API Naming

Use kebab-case.

Example

customer-profile-api

---

## Versioning

URI versioning

/api/customer-profile/v1

---

## REST Principles

Use nouns.

Avoid verbs.

Use HTTP methods correctly.

GET

Retrieve resources.

POST

Create resources.

PUT

Replace resources.

PATCH

Partial update.

DELETE

Delete resources.

---

## Security

OAuth2

OIDC

TLS 1.2+

RBAC

---

## Observability

Structured logging

Distributed tracing

Metrics

Health checks

---

## Documentation

Every significant architecture decision should be documented as an ADR.

Every API should include OpenAPI documentation.

Every component should define ownership and responsibilities.
