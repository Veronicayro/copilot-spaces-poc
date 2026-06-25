# BIAN Release 14

## What is BIAN?

BIAN (Banking Industry Architecture Network) is an industry standard that defines banking business capabilities through Service Domains.

Its objective is to standardize banking APIs, business services and capability boundaries.

---

## Main Concepts

### Service Domain

A Service Domain represents a business capability.

Examples:

- PartyLifecycleManagement
- CustomerOffer
- CustomerAgreement
- ProductFulfillment
- CustomerAccessEntitlement

---

### Control Record

Every Service Domain owns one Control Record.

Example

PartyLifecycleManagement

Control Record

Party Relationship Administrative Plan

---

### BIAN Operations

Standard operations include

- Initiate
- Update
- Retrieve
- Execute
- Exchange
- Control

---

## API Layers

Experience API

Used by web and mobile channels.

Business API

Orchestrates multiple business capabilities.

Domain API

Owns business data and business rules.

Support API

Provides technical capabilities such as notifications or document storage.

---

## Example

Digital Customer Onboarding

Business API

↓

Customer Profile Domain API

↓

Identity Verification Support API

↓

Notification Support API
