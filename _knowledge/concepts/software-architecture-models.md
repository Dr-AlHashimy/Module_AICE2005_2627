---
id: software-architecture-models
label: Software Architecture Models
tags: [concept, aice2005]
module: AICE2005
sessions: [6]
aims: []
prerequisites: [system-architecture]
related: [system-architecture]
---

# Software Architecture Models

## Definition

Beyond the general principles of system architecture, software systems are typically built from a recognisable catalogue of architecture models, each with a different communication pattern and coupling profile. Foundational models include monolithic (all functionality in one deployable unit — simple but hard to scale or redeploy piecemeal), N-tier/layered (presentation/application/data separated by APIs — better separation of concerns at the cost of network hops), and microservices (independently deployable, bounded-context services — fine-grained scaling and fault isolation at the cost of distributed-systems complexity); most organisations migrate from monolith through N-tier/modulith towards microservices rather than jumping directly. Interaction-centric models add client-server, service-oriented architecture (SOA, via an enterprise service bus), event-driven architecture (publish/subscribe, asynchronous), MVC/MVVM/MVP, and pipe-and-filter (sequential transformation stages), while modern hybrid patterns — serverless, event sourcing, CQRS (separate read/write paths), and composable/MACH (microservices, API-first, cloud-native, headless) — combine to fit different subsystems' needs within one system. At enterprise scale, architecture becomes a governance and observability problem as much as a structural one: architecture decision records, fitness functions, and observability (metrics, logs, traces) keep a continuously evolving architecture coherent, while frameworks such as TOGAF, Zachman, FEAF, and Gartner's outcome-driven approach provide (optional, mix-and-match) structure for aligning architecture decisions with organisational strategy, risk, and measurable value.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[system-architecture]]

## Covered in sessions

- [[AICE2005-session-06|Session 6]]
