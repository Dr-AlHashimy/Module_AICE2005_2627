---
id: advanced-source-control
label: Advanced Source Control
tags: [concept, aice2005]
module: AICE2005
sessions: [2]
aims: [a2]
prerequisites: []
related: [project-management, continuous-integration]
---

# Advanced Source Control

## Definition

Advanced source control goes beyond basic Git usage (`clone`, `checkout -b`, `commit`, `push`, `merge`/`rebase`) to the branching strategy, review discipline, and automation that let distributed teams work safely on tightly coupled systems. Branching strategies decompose work into parallel streams — feature branching isolates each change but raises later integration effort; GitFlow's long-lived `develop`/`release` branches suit regulated, slower-moving contexts; trunk-based development minimises branching and commits frequently to `main`, trading branch overhead for a dependency on strong CI/CD to keep `main` always releasable. Code review acts as a socio-technical feedback loop rather than a pure gate — formal reviews tie into compliance evidence in regulated domains, peer review relies on expert maintainers, and lightweight pull requests optimise for speed — and its rigour should match domain risk, since review that is too strict slows delivery while review that is too loose erodes quality. Automation (linting/style bots, dependency bots, CI bots) scales source control the way meta-models scale distributed design optimisation: bots absorb the cost of routine, repeatable checks so people can focus on design trade-offs, with commits tied to requirement IDs so that socio-technical intent stays traceable end to end.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[project-management]]
- [[continuous-integration]]

## Covered in sessions

- [[AICE2005-session-02|Session 2]]
