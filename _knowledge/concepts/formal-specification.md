---
id: formal-specification
label: Formal Specification
tags: [concept, aice2005]
module: AICE2005
sessions: [9]
aims: []
prerequisites: [identifying-interfaces]
related: [formal-verification]
---

# Formal Specification

## Definition

A formal specification describes a system's required behaviour or interface precisely enough to be checked automatically, rather than left as ambiguous prose. Examples include JSON/YAML schemas (e.g. CloudFormation, Kubernetes manifests), typed variables and module interfaces (e.g. Terraform), and policy-as-code (e.g. Open Policy Agent/Rego, cloud policy engines) that encode compliance rules such as encryption, logging, or segmentation requirements directly as enforceable, machine-readable artefacts. Formal specification supports reproducibility and enforcement: because the specification is executable, it can be validated automatically in CI/CD rather than relying on manual review, and it gives every stakeholder — engineers, auditors, regulators — a single unambiguous source of truth for what the system is supposed to do. It complements informal techniques like requirement modelling (MBSE/SysML), which formalises system behaviour and structure so it can be validated through simulation or model checking.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[formal-verification]]

## Covered in sessions

- [[AICE2005-session-09|Session 9]]
