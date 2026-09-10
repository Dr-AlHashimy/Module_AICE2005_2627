---
id: distributed-design
label: Distributed Design
tags: [concept, aice2005]
module: AICE2005
sessions: [1]
aims: []
prerequisites: [systematic-design]
related: [monolithic-design, systematic-design, decomposing-into-blocks, identifying-interfaces]
---

# Distributed Design

## Definition

Distributed design optimisation decomposes a global design problem into subproblems, each associated with a component or subsystem, which can then be optimised independently or in parallel. Coordination is required to ensure that the subproblem solutions remain compatible and converge to a system-level optimum — typically through shared interfaces, constraints, or surrogate/meta-models that describe cross-component behaviour (e.g. mass or stiffness feasibility) without requiring constant real-time coordination between teams. This shift from global to local design parallels organisational design: individual teams can work on parts of a system as long as shared protocols and interfaces are respected. Distributed design trades the global optimality of monolithic design for scalability and parallel development, at the risk of physically infeasible or suboptimal solutions if interfaces are poorly specified — the same trade-off that motivates decomposing systems into blocks and identifying interfaces later in the module.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[monolithic-design]]
- [[systematic-design]]
- [[decomposing-into-blocks]]
- [[identifying-interfaces]]

## Covered in sessions

- [[AICE2005-session-01|Session 1]]
