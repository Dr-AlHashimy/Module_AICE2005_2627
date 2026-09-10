---
id: formal-verification
label: Formal Verification
tags: [concept, aice2005]
module: AICE2005
sessions: [10]
aims: []
prerequisites: [formal-specification]
related: [testing-hw-sw-network-systems]
---

# Formal Verification

## Definition

Formal verification is the use of mathematical or model-based techniques to prove or automatically check that an implementation satisfies its formal specification, as opposed to testing, which samples behaviour on specific inputs. In practice this includes model checking and simulation against MBSE/SysML models built during requirement validation, and automated policy/compliance checks (policy-as-code, static analysis such as `tflint`/`checkov`) that verify infrastructure or configuration conforms to its declared schema before it is ever deployed. Because formal verification checks a specification exhaustively (within the model's scope) rather than sampling scenarios, it is especially valuable for interface contracts and safety- or compliance-critical behaviour, where an undetected violation would be expensive or dangerous to discover only through testing in production.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[testing-hw-sw-network-systems]]

## Covered in sessions

- [[AICE2005-session-10|Session 10]]
