# Stopping Rule and Termination Conditions

## Purpose

This document defines the non-negotiable stopping rules for Phase 1 of the
Living-System Discrimination Hypothesis.

Its purpose is to ensure that the project:
- can fail decisively,
- cannot be rescued post hoc,
- and terminates cleanly if the hypothesis is not supported.

---

## Binary Gate

Phase 1 operates as a **binary gate**.

There are only two admissible outcomes:

1. **Pass Phase 1** (conditional continuation to replication)
2. **Fail Phase 1** (project termination)

No intermediate or ambiguous outcomes are permitted.

---

## Primary Stopping Criterion

### Failure (Project Termination)

The project **terminates immediately** if:

- The preregistered 95% confidence interval (Wilson interval on pooled trials)
  for the primary endpoint **includes 0.50**.

Upon failure:
- The Living-System Discrimination Hypothesis (Phase 1) is rejected.
- No further data collection, analysis, or modification is allowed.
- The null result is prepared for public release.
- The repository is archived or marked as concluded.

No reinterpretation, reanalysis, or theory modification is permitted.

---

### Success (Conditional Continuation)

Phase 1 is considered **successful** if and only if:

- The lower bound of the preregistered 95% confidence interval exceeds 0.50, **and**
- The preregistered minimum effect size threshold is met, **and**
- Performance direction is consistent across experimenters (per preregistration).

Success does **not** validate any explanatory framework.
It indicates only that a signal may exist and requires independent replication.

---

## Explicit Prohibitions

The following actions are explicitly prohibited once data collection begins:

- Changing the hypothesis
- Modifying inclusion or exclusion criteria
- Adjusting the analysis plan
- Introducing new control conditions
- Reframing failure as “inconclusive”
- Continuing data collection after failure criteria are met

Any violation invalidates the run.

---

## Publication Commitment

Regardless of outcome:

- Results will be documented and made publicly available.
- Null results will be shared to prevent duplication of effort.
- No selective reporting is permitted.

---

## Phase Boundary

This stopping rule applies **only** to Phase 1.

Advancement beyond Phase 1 requires:
- a successful Phase 1 outcome,
- independent replication,
- and a new manifest defining scope and intent.

---

## Status

Locked.

This stopping rule is binding once preregistration is submitted.
