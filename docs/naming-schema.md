# Naming Schema (Draft)

**Status:** Draft  
**Date:** February 1st, 2026

---

## Purpose

This document defines a standardized naming and referencing scheme for concepts, frameworks, primitives, and scenarios in this repository.

The goals are:
- Stable references over time
- Clear separation between structure and cultural mnemonic
- Machine-sortable identifiers
- Human-readable meaning

---

## Canonical Format

```
CC-L<Level>-<Index> : <Descriptive Name> (<Reference>)
```

Example:

```
CC-L3-001 : Logic-Primacy Constraint Agent (Surak)
```

---

## Components

### Prefix: CC

**CC** denotes *Covenant Concept* (or *Constraint Concept*). The prefix is structural and must not encode meaning beyond namespace.

---

### Level (L1–L5)

Levels indicate the primary layer at which the concept operates:

- **L1** — Component / Primitive
- **L2** — Loop / Interaction
- **L3** — Agent / Architecture
- **L4** — System / Multi-agent
- **L5** — Emergent / Meta-system

Levels are classificatory, not evaluative.

---

### Index

- Three-digit, zero-padded integer (`001`, `002`, …)
- Sequential assignment
- No semantic meaning encoded

Once assigned, an index must not be reused.

---

### Descriptive Name

The descriptive name must:
- Be technically precise
- Avoid metaphor where possible
- Reflect actual behavior or structure

This name may evolve, but the ID must remain stable.

---

### Reference

The reference is a **human mnemonic anchor**:

- May be cultural, historical, or personal
- Has no structural meaning
- Must be spelled correctly and frozen once chosen

Example reference:
- **Surak** — Vulcan philosopher (Star Trek canon)

---

## Rules

- All new frameworks and primitives must receive an ID
- Draft concepts must still follow the schema
- References must not substitute for descriptive names
- Structural discussions should prefer IDs over references

---

## Notes

This schema is locked pending explicit revision. Any change requires updating this document.
