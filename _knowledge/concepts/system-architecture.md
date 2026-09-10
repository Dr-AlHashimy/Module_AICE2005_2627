---
id: system-architecture
label: System Architecture
tags: [concept, aice2005]
module: AICE2005
sessions: [6]
aims: []
prerequisites: [functional-non-functional-requirements]
related: [decomposing-into-blocks, systematic-design, software-architecture-models]
---

# System Architecture

## Definition

System architecture defines how a system's components collaborate, how responsibilities are separated, and how the solution adapts to change — without it, teams encounter integration surprises, coupling, and brittle designs. Common architectural styles include layered (presentation/business/data), service-oriented (loosely coupled services via contracts), event-driven (publish/subscribe, asynchronous), and component-based (reusable modules with defined interfaces). Architecting a system involves choosing a decomposition strategy — horizontal (splitting peers at the same abstraction level, e.g. microservices) versus vertical (separating system-level goals from component implementations) — coordinated through shared metrics and surrogate/meta-models so that local optimisation does not harm global outcomes. Design patterns (creational, structural, behavioural for software; bus controller, pipeline, and redundancy for hardware/embedded; MVC and publisher-subscriber as cross-domain patterns) provide proven templates for recurring structural and behavioural problems, while stakeholder analysis and boundary scoping ensure the architecture reflects real operator, maintainer, regulator, and user needs.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[decomposing-into-blocks]]
- [[systematic-design]]
- [[software-architecture-models]]

## Covered in sessions

- [[AICE2005-session-06|Session 6]]
