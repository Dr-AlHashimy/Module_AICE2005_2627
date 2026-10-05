---
id: systemic-design
label: Systemic Design
tags: [concept, aice2005]
module: AICE2005
sessions: [1]
aims: []
prerequisites: [systems-thinking]
related: [systems-thinking, systematic-design]
examples: [social-media-algorithm-feedback]
---

# Systemic Design

## Definition

A design approach that integrates systems thinking into the design process to address complex, interconnected, socio-technical challenges involving multiple stakeholders and dynamic relationships.

Key characteristics:

- Emphasises relationships, feedback loops, and emergent behaviours
- Integrates qualitative and quantitative analysis
- Focused on sense-making and co-creation in messy, real-world contexts
- Often applied to sustainability, healthcare, policy, education, and ecosystems

### Systemic Design Principles

A common systemic design mindset includes:

- Acknowledging interconnections
- Redefining waste as a resource
- Designing self-organising systems
- Using feedback as a guide to adaptive improvement

These mindsets are increasingly important as engineers face challenges that are not purely technical but socio-technical, requiring both human and machine systems to work harmoniously. 

### Worked Example: Redesigning a Recommender System

Where [[systems-thinking]] *diagnoses* the algorithm/user feedback loop that produces filter bubbles (see [[social-media-algorithm-feedback]]), systemic design *redesigns the whole system*, not just the algorithm:

- Change recommendation weights to penalise extreme content
- Redesign the UI to surface opposing viewpoints and trigger reflection
- Change creator incentives from engagement-maximisation to quality
- Add circuit breakers that inject diverse content when a feed becomes too homogeneous
- Monitor for emergent polarisation across the whole platform

These interventions only work *together*: changing the algorithm without changing incentives still lets creators game the system; showing opposing views without changing the algorithm gets them ignored. Systemic design means designing across the system, not one component at a time — see [[systematic-design]] for how the same scenario looks run as a phased process instead.

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[systems-thinking]]
- [[systematic-design]]

## Examples

- [[social-media-algorithm-feedback|Social Media Algorithm: Feedback Loops and Emergent Behaviour]]

## Covered in sessions

- [[AICE2005-session-01|Session 1]]
