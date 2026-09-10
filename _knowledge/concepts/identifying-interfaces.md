---
id: identifying-interfaces
label: Identifying Interfaces
tags: [concept, aice2005]
module: AICE2005
sessions: [8]
aims: [b2]
prerequisites: [decomposing-into-blocks]
related: [designing-apis-protocols, decomposing-into-blocks]
---

# Identifying Interfaces

## Definition

An interface defines how information, energy, or material is exchanged at the boundary between two components, and identifying interfaces well is what allows components to be developed and optimised independently without producing physically infeasible or incompatible designs. Interfaces fall into three complementary categories: functional (what one block provides to another, e.g. a torque command to a motor), physical (mechanical, electrical, or material couplings — tolerances, connectors, environmental constraints), and informational (data formats, timing, synchronisation, security/privacy protocols) — a single signal (e.g. a temperature reading) can embody all three at once. In multi-component systems, interfaces routinely cross domains — hardware (analog/digital signals, mechanical couplings), software (APIs, middleware, message buses), and learning/human-AI (dashboards, reward signals, UX interactions) — and system boundaries are as much organisational as technical, so interface identification must also map who owns each subsystem, what data crosses organisational lines, and how ethics, privacy, and security are enforced at each hand-off.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[designing-apis-protocols]]
- [[decomposing-into-blocks]]

## Covered in sessions

- [[AICE2005-session-08|Session 8]]
