---
id: testing-hw-sw-network-systems
label: Testing Hardware, Software and Network Systems
tags: [concept, aice2005]
module: AICE2005
sessions: [10]
aims: [d1]
prerequisites: [continuous-integration]
related: [formal-verification]
---

# Testing Hardware, Software and Network Systems

## Definition

Testing in systemic design begins during requirements analysis, not after implementation: requirements define what to test, and testing in turn validates and refines requirements through a recursive feedback loop. Software testing layers from small to large — unit (atomic functions), integration (module interfaces), system (end-to-end scenarios), acceptance (stakeholder criteria), and destructive/fault-injection (stress and chaos tests that reveal hidden failure modes). Hardware testing uses its own toolkit: non-destructive testing (NDT — ultrasonic, X-ray, electrical inspection) to detect flaws without damage, destructive testing (tensile, fatigue, thermal) to explore failure envelopes, burn-in testing to surface early-life failures, and fault injection to validate resilience. Every requirement should be linked to a test case in a traceability matrix (system, component, or integration level) so coverage is verifiable and no requirement goes untested. Distributed systems mirror distributed optimisation: tests decompose into component-level sub-tests, aggregated via meta-models into system-level reliability estimates, with continuous verification embedding this into CI/CD (CI, CT, HiL simulations, automated regression).

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[formal-verification]]

## Covered in sessions

- [[AICE2005-session-10|Session 10]]
