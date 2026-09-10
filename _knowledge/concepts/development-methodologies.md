---
id: development-methodologies
label: Development Methodologies
tags: [concept, aice2005]
module: AICE2005
sessions: [11]
aims: [a2, a3]
prerequisites: []
related: [project-management]
---

# Development Methodologies

## Definition

A development methodology is a system-level control strategy: it bounds uncertainty, regulates how a system evolves, and coordinates distributed contributors and components over time. Predictive methodologies (Waterfall, V-Model, RUP) assume relatively stable requirements and a predictable environment — the V-Model in particular pairs each design stage (requirements, system design, architecture, module design) with a matching verification stage (acceptance, system, integration, unit testing), giving strong traceability at the cost of expensive late-stage change. Adaptive methodologies (Agile — Scrum, Kanban, Extreme Programming) assume requirements evolve and value emerges through iteration, trading some traceability and up-front documentation for fast feedback loops and responsiveness. Risk-aware and iterative models (Spiral, Incremental, RAD, Prototype) sit between the two, using repeated cycles of planning, risk analysis, and evaluation to surface learning sooner without abandoning structure. In multi-component systems no single model fits every subsystem: hybrid strategies commonly hold an architecture "backbone" stable (V-Model/Waterfall for hardware or regulated components) while software or ML subsystems iterate with Agile inside it, synchronised through shared architecture reviews and integration milestones — mirroring the informed-decomposition pattern of global constraints plus local iteration used in distributed design optimisation.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[project-management]]

## Covered in sessions

- [[AICE2005-session-11|Session 11]]
