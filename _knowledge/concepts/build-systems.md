---
id: build-systems
label: Build Systems
tags: [concept, aice2005]
module: AICE2005
sessions: [3]
aims: []
prerequisites: []
related: [continuous-integration]
---

# Build Systems

## Definition

A build system automates turning source artefacts (code, infrastructure definitions, configuration) into a validated, deployable output through a repeatable pipeline. A typical pipeline stages this as: validate (e.g. `terraform validate`), lint (static analysis for style and known anti-patterns), plan (preview the diff/impact before applying), approve (a human-in-the-loop gate for consequential changes), apply (the automated, controlled build/deploy step), and post-build tests (smoke tests or integration checks against the freshly built artefact). Build systems formalise the "cattle, not pets" principle for infrastructure and code alike: environments and artefacts should be consistent, reproducible, and disposable rather than hand-tuned and unique, which is what makes automated testing and rollback trustworthy.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[continuous-integration]]

## Covered in sessions

- [[AICE2005-session-03|Session 3]]
