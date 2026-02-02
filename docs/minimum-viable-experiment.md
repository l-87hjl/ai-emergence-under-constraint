# Minimum Viable Experiment (MVE)

**Status:** Draft  
**Date:** February 1st, 2026

---

## Purpose

The Minimum Viable Experiment (MVE) defines the smallest experimental setup capable of testing the project’s emergence definition in a reproducible and comparative manner.

---

## Experimental Setup

- Scenario: `scenarios/minimal-toy-emergence.md`
- Single agent per run
- Fixed constraint set
- No reward shaping beyond constraint enforcement

---

## Variables

Held constant:
- Constraints
- Environment dynamics
- Evaluation criteria

Varied:
- Framework architecture (e.g., CC-L3-001 Surak)

---

## Procedure

1. Initialize agent under fixed constraints
2. Run for a fixed number of steps or until termination
3. Record internal state transitions (where observable)
4. Evaluate behavior using the comparative checklist

---

## Success Criteria

The experiment is considered valid if it can:
- Be repeated with identical conditions
- Be run across multiple frameworks
- Produce observable differences in behavior

---

## Notes

This MVE is intentionally minimal and should precede any scaling efforts.
