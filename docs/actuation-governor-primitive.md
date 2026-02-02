# Actuation Governor Primitive (Draft)

**Status:** Draft  
**Date:** February 1st, 2026

---

## Definition

An **Actuation Governor** is a primitive that mediates between an actor’s declared intent and any irreversible change to the world.

It does not evaluate correctness, morality, or optimality of intent. It constrains *how* intent may be expressed as action.

---

## Core Function

The Actuation Governor enforces a fixed structure:

```
Actor
  ↓
Declared Intent
  ↓
Governor Interface
  ↓
Constrained Actuation
  ↓
World State Change
```

The governor is the final gate before actuation.

---

## Properties

An Actuation Governor:

- Requires **explicit intent declaration**
- Restricts **scope of permissible action**
- Enforces **non-sovereignty** (the actor does not own the system)
- Produces **legible, inspectable actions**
- Can halt, delay, or reject actions deterministically

---

## What It Is Not

An Actuation Governor is **not**:

- A cognition or reasoning system
- A value-learning or alignment module
- A policy engine
- A reward or punishment mechanism

---

## Relationship to Covenant

In Covenant-based systems, the Actuation Governor occupies the **Governor Layer**.

It ensures that power is mediated by design rather than trust in cognition.

---

## Notes

This primitive is architecture-agnostic and may govern human or non-human actors.
