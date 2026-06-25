# Architecture Decision Records

## What is an ADR?

An ADR documents an important architectural decision.

It explains

- What was decided
- Why it was decided
- Alternatives considered
- Consequences

---

## Example ADR

Decision

Use PostgreSQL.

Reason

Strong ACID guarantees.

Alternatives

- MongoDB
- Event Sourcing

Consequences

- Strong consistency
- Easier relational queries

---

## Example ADR

Decision

Use Transactional Outbox.

Reason

Prevent the dual-write problem.

Alternatives

- Direct publish
- Event sourcing

Consequences

Reliable event publication.
