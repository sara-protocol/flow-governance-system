# Contributing to SARA Flow Governance

This repository is governed by protocol-first principles.

## Priority Order
Protocol > Product > Design > Engineering

No contribution may violate this order.

---

## Non-Negotiable Constraints

Any contribution that does any of the following
WILL NOT be accepted:

- Weakens or bypasses pause points
- Reduces or obscures exit rights
- Converts system health metrics into user scores
- Optimises engagement, retention, or time-on-task
  at the cost of cognitive autonomy

---

## Protocol Changes

Changes to `/protocol` require:

1. A dedicated PR
2. Explicit statement of:
   - What boundary is being changed
   - Why it is necessary
   - What new risks it introduces
3. Version bump in `protocol/VERSION.md`

---

## Engineering Contributions

Engineering may not:
- Reinterpret protocol intent
- Implement “temporary” bypasses
- Replace governance constraints with UX nudges

If a protocol requirement is technically difficult,
the correct action is to stop and escalate.

---

## Final Principle

If a feature makes the system
more engaging but less governable,
it is a regression.
