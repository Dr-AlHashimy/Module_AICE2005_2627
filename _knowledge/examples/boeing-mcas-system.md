---
id: boeing-mcas-system-failure
label: Boeing 737 MAX - System Integration Failure
tags: [example, aice2005, system-theory, failure, cyber-physical]
module: AICE2005
concepts: [system-theory, systems-thinking, feedback-loops, cyber-physical-systems]
sessions: [1]
---

# Boeing 737 MAX: Local Optimization, System Failure

## The System

A modern aircraft is a coupled system: aerodynamics, pilot training, mechanical systems, and software control. Each component must work together.

## What Happened

**Boeing engineers solved an aerodynamics problem:** New, larger engines shifted the center of lift. The plane became harder to handle in certain high-angle-of-attack situations.

**Local solution:** Add software (MCAS—Maneuvering Characteristics Augmentation System) to automatically pitch down if sensors detect high angle of attack. Problem solved.

**But the system was larger than the software fix:**

The feedback loop nobody managed:
- New aerodynamics → plane behaves differently than previous 737s
- Pilots trained on old 737s → don't know new handling characteristics
- MCAS activates to "fix" the new handling
- But pilots don't know MCAS exists (not in training)
- Sensor fails → MCAS gets wrong data
- MCAS commands pitch-down that shouldn't happen
- Pilots try to recover but MCAS keeps fighting them
- Pilots can't override the automated system logic
- **346 people died in two crashes**

## Why Systems Thinking Was Missing

Engineers optimized the aerodynamic component in isolation:
- Aerodynamic problem → add control software
- Software was elegant and precise
- But it created a new component (MCAS) that interacted with the human-machine system in ways nobody fully anticipated

The system included:
- Aircraft aerodynamics (changed)
- Pilot training (unchanged)
- Pilot knowledge (outdated)
- Software automation (new, hidden)
- Sensor reliability (not considered)
- Manual override capability (inadequate)

Nobody managed these as an interconnected system. The fix in one domain (aerodynamics) created hidden assumptions in another (pilot knowledge and automation).

## The Consequence

Two crashes, 346 deaths, 737 MAX grounded for 20 months, billions in losses, erosion of trust in Boeing.

## System Theory Insight

In cyber-physical systems, changing one component (aerodynamics) cascades through others (pilot training needs, automation design, sensor requirements). You cannot optimize components in isolation. You must:
- Map the entire coupled system (physical + human + software)
- Identify all feedback loops and dependencies
- Test how changes propagate
- Ensure humans understand and can override automation

Local optimization without systems thinking killed 346 people.

## Related Concepts

- [[system-theory]]
- [[systems-thinking]]
- [[cyber-physical-systems]]
- [[feedback-loops]]
- [[emergent-behavior]]
