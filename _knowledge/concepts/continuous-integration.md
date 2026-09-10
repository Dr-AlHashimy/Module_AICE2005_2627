---
id: continuous-integration
label: Continuous Integration (Hardware and Software)
tags: [concept, aice2005]
module: AICE2005
sessions: [3]
aims: [d1]
prerequisites: [build-systems]
related: [testing-hw-sw-network-systems]
---

# Continuous Integration (Hardware and Software)

## Definition

Continuous integration (CI) is the practice of frequently merging and automatically building, linting, and testing changes so that integration problems are caught within minutes of being introduced rather than discovered late. A typical CI/CD gate sequence layers checks by cost and confidence: linting → unit tests → integration tests → hardware-in-the-loop (HiL) or contract tests → staging deployment, with each gate a cheaper filter than the one after it. For hardware-in-the-loop and multi-component systems, CI extends into continuous testing (CT): automated regression suites re-run against physical or simulated hardware so that evolving requirements stay verified, and GitOps tooling (e.g. ArgoCD/Flux, Atlantis/Terraform Cloud) keeps deployed state continuously reconciled with the declared configuration in version control, with automated rollbacks triggered by policy violations.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[testing-hw-sw-network-systems]]

## Covered in sessions

- [[AICE2005-session-03|Session 3]]
