---
id: git-workflow-system
label: Git Workflow as a System
tags: [example, aice2005, system-theory]
module: AICE2005
concepts: [system-theory, systems-thinking, feedback-loops, systemic-design]
sessions: [1]
---

# Git Workflow: Feedback Loops and System Design

## The System

A Git workflow contains interdependent components:

1. **Branch strategy** — how long developers work on branches before integration
2. **Code review process** — how long review takes, whether it blocks new work
3. **CI/CD pipeline** — test speed, deployment frequency
4. **Developer behaviour** — when they integrate, how they commit

These are not independent. They form feedback loops that drive system behaviour.

## Feedback Loops in Git

**The merge conflict loop (positive feedback):**
- Long-lived branches → harder merges due to divergence
- Difficult merges → developers delay integration
- Delayed integration → branches live longer
- Longer branches → even harder merges

Result: Merge conflicts become the norm. Nobody planned this; it emerges from the system structure.

**The blocked review loop (positive feedback):**
- Code review is slow (takes 3 days)
- Developers accumulate work while waiting
- More commits on feature branches
- Review becomes harder to understand
- Review takes even longer

Result: Backed-up pull requests, longer branches, more conflicts.

**The deployment pressure loop (positive feedback):**
- Infrequent deployments (once per month)
- Developers batch features to justify deployment effort
- Large batches create more merge conflicts
- Conflicts delay deployment further
- Pressure to batch more increases

Result: Slow, risky deployments.

## Why Systematic Thinking Fails

Optimizing one component in isolation fails:
- Force shorter branches without fixing slow code review → developers still accumulate work while waiting
- Speed up code review without fixing batch deployments → reviewers still overwhelmed because changes are batched
- Deploy frequently without fixing branch strategy → frequent deployments hit constant merge conflicts

Each "fix" ignores system interactions.

## Systemic Design: Redesign the Whole System

Design practices that reinforce each other:

- **Short branches** (1-2 days max) force frequent integration
- **Async code review** that doesn't block—reviews happen in parallel with new work
- **Fast, reliable CI** (tests in minutes, not hours) gives quick feedback
- **Frequent deployments** (daily or multiple times per day) remove pressure to batch changes

These practices work *together*:
- Short branches lower merge risk → easier reviews → faster review time → developers integrate more readily
- Frequent deploys remove pressure to batch → smaller batches → faster reviews → developers accept short branches
- Fast CI → developers discover conflicts early → shorter debugging cycles → easier to maintain short branches

Feedback loops align and reinforce each other.

## Emergent Behaviour: Unintended Consequences

If you add code review without redesigning branches:
- Review backlog forms (unintended)
- Developers keep working on branches (unintended)
- Branches live longer (unintended)
- Merge conflicts increase (unintended)

The system adapted in ways nobody planned. Systems thinking predicts this: delayed feedback → longer work → harder integration.

## The System Theory Insight

You cannot optimize Git workflow by changing one practice. The workflow is a system. Each component affects others through feedback loops. Design must account for the whole system, not just individual parts.

Solutions require identifying:
- Which feedback loops drive current behaviour
- Which loops are virtuous (reinforce good practices)
- Which are vicious (create problems)
- How to align practices so feedback loops reinforce each other

## Related Concepts

- [[system-theory]]
- [[systems-thinking]]
- [[systemic-design]]
- [[feedback-loops]]
