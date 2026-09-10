---
id: functional-non-functional-requirements
label: Functional and Non-Functional Requirements
tags: [concept, aice2005]
module: AICE2005
sessions: [4]
aims: []
prerequisites: []
related: [requirements-gathering, system-architecture]
---

# Functional and Non-Functional Requirements

## Definition

A requirement is a statement of a capability, function, or quality that a system must have, or a constraint it must operate under, that addresses stakeholder needs. Functional Requirements (FRs) describe *what* the system should do — observable, testable behaviours and services, typically phrased as "The system shall..." (e.g. "The system shall allow user login"). Non-Functional Requirements (NFRs) describe *how well* the system performs those functions — quality attributes and constraints such as performance, reliability, usability, and security (e.g. "The system shall respond within 250 ms"). NFRs are harder to elicit and verify than FRs, are often invisible until violated, and are cross-cutting concerns that drive major architectural decisions (technology stack, hardware specification, deployment strategy, fault tolerance) rather than individual features. ISO/IEC 25010:2011 defines common NFR categories: performance, reliability, portability, compatibility, usability, security, and maintainability. Good requirements are correct, unambiguous, complete, consistent, verifiable, traceable, feasible, and prioritised; common pitfalls include vagueness ("the system shall be fast"), unmeasurable statements ("user-friendly"), and NFRs being under-tested or dropped in Agile sprints.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[requirements-gathering]]
- [[system-architecture]]

## Covered in sessions

- [[AICE2005-session-04|Session 4]]
