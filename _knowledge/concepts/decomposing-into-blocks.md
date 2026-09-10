---
id: decomposing-into-blocks
label: Decomposing into Blocks
tags: [concept, aice2005]
module: AICE2005
sessions: [7]
aims: [b1]
prerequisites: [system-architecture]
related: [identifying-interfaces, system-architecture]
---

# Decomposing into Blocks

## Definition

Decomposing a system into blocks means breaking it into a hierarchy of manageable subsystems and components — e.g. system level (the whole product), subsystems (major functional groupings), and components (individual parts) — so that each can be developed, optimised, and tested with some independence while the whole remains coherent. A block diagram is the visual language for this: each block exposes inputs, outputs, and an internal function, connected by information, energy, or material flows, with feedback loops showing how outputs regulate inputs. Good decomposition follows informed decomposition principles: high cohesion (each module has a single, focused responsibility) and low coupling (minimal, well-documented dependencies between modules), because tightly coupled modules resist change like a stiff mechanical joint. Interface variables (e.g. mass, stiffness, timing, control signals) must be defined explicitly so that subsystems can be optimised locally without breaking system-level goals — the same principle that lets infrastructure-as- code split a deployment into networking, compute, storage, identity, and monitoring modules.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[identifying-interfaces]]
- [[system-architecture]]

## Covered in sessions

- [[AICE2005-session-07|Session 7]]
