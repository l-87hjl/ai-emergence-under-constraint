# Covenant Knowledge & Idea Management (Draft)

**Status:** Draft  
**Date:** February 1st, 2026

This document defines how Covenant-related ideas, artifacts, and discussions are tracked, classified, and preserved **without requiring full public disclosure** or raw conversation dumps.

The goal is to prevent loss of intellectual work, avoid reinvention, and maintain strategic control over what is shared publicly.

---

## 1. Off-Repo Knowledge Ingestion (Private Source → Public Structure)

### Problem

Significant Covenant material exists as:
- Chat transcripts
- PDFs
- Ad hoc notes
- Code fragments generated in tools like Claude

These materials are:
- Not safely public
- Not indexed
- At risk of being forgotten or duplicated

### Policy

- **Raw material remains private** (not committed)
- Only **parsed, distilled artifacts** enter the repo
- No full transcripts are committed

### Allowed Artifacts

- Concept summaries
- Design abstractions
- Decision records
- Redacted pseudocode
- Lessons learned

---

## 2. Idea Triage: Internal vs Publishable

Every significant idea should be classified into one of three buckets:

### A. Core Covenant Concepts

- Belong in this repo
- Shape definitions, frameworks, or philosophy
- May evolve over time

### B. Publishable Derivatives

- Suitable for Medium / Substack / essays
- Can reference Covenant ideas without revealing internals
- Logged as **article candidates**

### C. Non-Public / Strategic

- Not published
- Preserved only as internal notes or summaries
- May be revisited later

---

## 3. Article & Essay Log

Maintain a lightweight log (titles + one paragraph) for:
- Ideas that could become articles
- Ideas explicitly **not** to be published (with reason)

Suggested file:
```
docs/article-ideas.md
```

---

## 4. Disputed or Ambiguous Core Ideas

Some Covenant elements are **legitimately contested**, not resolved.

Examples:
- Whether a *frozen LLM* is integral to Covenant
- Whether Covenant assumes a pre-trained or untrained AI
- Whether Covenant is an architecture, a governance layer, or a philosophy

### Policy

- Disagreement is documented, not erased
- Multiple interpretations may coexist
- Revisions should reference earlier positions

Suggested file:
```
docs/covenant-open-questions.md
```

---

## 5. Covenant Concept Strata (Provisional)

Covenant currently spans at least three conceptual layers:

1. **Technical / Architectural**  
   Constraint and governance layers interacting with AI systems

2. **Transitional / Strategic**  
   Covenant as a time-bound negotiation window before capability asymmetry

3. **Philosophical / Ethical**  
   Covenant as a model of negotiated otherness and mutual restraint

These layers should not be collapsed prematurely.

---

## 6. Practical Constraints (Author Context)

Development constraints to assume:

- Primary device: phone
- Secondary device: iPad Pro
- No local development environment
- Reliance on cloud tools and web interfaces

Docs and workflows should remain:
- Mobile-readable
- Markdown-first
- Low-friction

---

## 7. Principle

> Covenant work should be **rememberable, revisitable, and revisable** without requiring raw disclosure.

---

## Notes

This document is governance for knowledge, not a content dump.
