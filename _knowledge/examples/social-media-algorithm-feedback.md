---
id: social-media-algorithm-feedback
label: Social Media Algorithm Feedback Loops
tags: [example, aice2005, system-theory]
module: AICE2005
concepts: [system-theory, systems-thinking, feedback-loops]
sessions: [1]
---

# Social Media Algorithm: Feedback Loops and Emergent Behaviour

## Social Media Algorithm Example

A social media platform contains three coupled components:

1. **The recommendation algorithm** — learns from user engagement, ranks content
2. **User behaviour** — users see recommendations and decide what to engage with
3. **Content ecosystem** — posts, creators, discourse shaped by what algorithms amplify

These are not independent. They form a feedback loop.

## How It Works

**Initial state:** Algorithm recommends diverse content based on past engagement.

**Positive feedback loop:**
- User engages with political content (likes, shares, comments)
- Algorithm learns: this user likes political content
- Algorithm recommends more political content to this user
- More political engagement trains algorithm further
- Algorithm recommends even more political content

**Emergence:** After weeks, the user's feed contains nearly only political content—often increasingly extreme versions. No engineer programmed polarization. No single decision caused it. It emerged from the feedback loop between algorithm and user behaviour.

**System-level effect:** Across millions of users, this creates filter bubbles, where people see only views that confirm their existing beliefs. Discourse fragments. Misinformation spreads in bubbles. Trust in institutions erodes.

## Why Traditional Thinking Fails

Optimizing the algorithm alone won't fix this:
- Tweaking recommendations to "show more diverse content" is ignored if users ignore it (user behaviour is part of the system)
- Removing engagement signals changes incentives but creates new feedback loops elsewhere
- Individual features work fine in isolation; system behaviour is unpredictable

## The System Theory Insight

You cannot understand the algorithm's impact without understanding the user-algorithm feedback loop as a single system. The algorithm and user behaviour are interdependent. Change one part and you destabilize the whole. Emergent behaviours (polarization, filter bubbles) come from the system, not from any component.

Solutions require systems thinking:
- Add negative feedback (e.g., expose users to opposing views, but measure actual engagement changes)
- Change incentive structures across the entire platform, not just the algorithm
- Monitor emergent behaviours, not just algorithm metrics

### Worked Example: A Systemic Redesign Process

Where systems-thinking *diagnoses* the algorithm/user feedback loop that produces filter bubbles , systemic design *redesigns the whole system*, not just the algorithm:

- Change recommendation weights to penalise extreme content
- Redesign the UI to surface opposing viewpoints and trigger reflection
- Change creator incentives from engagement-maximisation to quality
- Add circuit breakers that inject diverse content when a feed becomes too homogeneous
- Monitor for emergent polarisation across the whole platform

These interventions only work *together*: changing the algorithm without changing incentives still lets creators game the system; showing opposing views without changing the algorithm gets them ignored. Systemic design means designing across the system, not one component at a time —  systematic-design for how the same scenario looks run as a phased process instead.


### Worked Example: A Systematic Redesign Process

Continuing the same scenario as systemic-design's worked example, a systematic approach to redesigning a recommender system looks like an ordered checklist:

1. Audit the current recommendation algorithm
2. Design a new weighting scheme
3. Build A/B test infrastructure
4. Run tests on 10% of users
5. Measure engagement metrics
6. Roll out to 100% if metrics improve

Each step is methodical and auditable — but, taken alone, isolated: step 1 doesn't show how it affects step 4, or how improving one metric breaks another part of the system. That's the gap systemic-design closes.


## Related Concepts

- [[system-theory]]
- [[systems-thinking]]
- [[feedback-loops]]
- [[emergent-behavior]]
