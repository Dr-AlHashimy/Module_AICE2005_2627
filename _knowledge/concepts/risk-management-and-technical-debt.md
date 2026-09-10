---
id: risk-management-and-technical-debt
label: Risk Management and Technical Debt
tags: [concept, aice2005]
module: AICE2005
sessions: [11]
aims: [a3]
prerequisites: [project-management]
related: [project-management]
---

# Risk Management and Technical Debt

## Definition

Risk management and technical debt are two sides of the same systemic problem: unmanaged risk produces technical debt, and technical debt, left unpaid, becomes systemic risk. Risk analysis is prospective — assessing likelihood and impact before failure (using tools like FMEA, risk matrices, or Monte Carlo simulation) to prioritise mitigations — while forensic analysis is retrospective, investigating an actual failure's evidence (logs, sensor data, physical inspection) to reconstruct root causes and propagation chains; each improves the other, as forensic evidence updates risk models and risk pathways guide what forensic investigations should look for. Technical debt in multi-disciplinary systems is not just a software concept: it spans hardware debt (over-sized components, rushed substitutions), software debt (hard-coded parameters, thin tests), integration debt (interface mismatches, undocumented APIs), and organisational debt (siloed teams, unclear ownership) — and it tends to accumulate exactly at interfaces, subsystem boundaries, opaque/black-box components, and unclear requirements. Quantitative tools such as Risk Score (likelihood × impact), FMEA's Risk Priority Number (severity × occurrence × detection), and Risk Reduction ((risk before − risk after) / risk before) turn qualitative concern into prioritised, justifiable action, mitigated through architectural strategies (modular interfaces, formal API specs), process strategies (CI for hardware and software, debt registers, refactor windows), analytical strategies (sensitivity analysis, robust optimisation), and systems-thinking strategies (causal loop mapping, leverage-point identification, stakeholder co-design).

## Why it matters

<!-- Add context: why does this concept matter for a PhD researcher? -->

## See also

- [[project-management]]

## Covered in sessions

- [[AICE2005-session-11|Session 11]]
