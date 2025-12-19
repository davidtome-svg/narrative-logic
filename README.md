# Canon: Narrative admissibility, before judgement

**Status:** Phase 2 (Frozen)  
**Date frozen:** 19 December 2025  
**Deployment posture:** Containerised, offline-capable  
**Outputs:** Traceable structure, optional audit bundle

---

## Overview
Canon is a **pre-evaluative admissibility layer** designed for governance-first environments where narratives are relied upon in audit, assurance, and decision workflows.

Canon checks whether required structural elements are **explicitly stated** in text and refuses admissibility where they are absent.

---

## The problem
In many governance and evaluation processes, narratives are treated as evidence.

When required details are not explicitly stated, reviewers and systems may silently fill gaps with assumptions. Over time, those assumptions can be mistaken for evidence, creating avoidable governance and assurance risk.

---

## What Canon does
- Checks whether required structural elements are **explicitly stated**
- Returns a refusal-biased admissibility result (admissible / not admissible)
- Makes absence visible rather than inferred
- Provides traceability to source text via verbatim spans and offsets
- Optionally produces an audit bundle (hash + returned structure + timestamps/version labels)

---

## What Canon is not
- Not an AI or machine-learning system
- Not a scorer, ranker, or evaluator of quality
- Not a decision-maker or approval mechanism
- Not a clinical system or decision support tool
- Does not infer meaning or fill gaps

---

## Operating principles
- **Deterministic:** same input → same output  
- **Non-inferential:** records only what is explicitly stated  
- **Refusal-biased:** absence yields non-admissible  
- **Audit-legible:** outputs traceable to source text  

---

## Why admissibility comes first
Many failures occur upstream of judgement, when structurally incomplete narratives are relied upon and missing details are silently supplied by inference.

Canon exists to enforce explicitness before narratives are evaluated, audited, or used downstream by humans or AI systems.

*Canon reports structural admissibility only. It does not assert correctness, quality, safety, truth, or merit.*

---

## Contact
Canon is available for discussion where there is a concrete governance, audit, assurance, or AI-workflow use case.

Operational details are shared **only under NDA**.

**Contact:**  
david@narrativelogic.co.uk  
**Subject:** Canon — NDA discussion request

---

© Narrative Logic Ltd. All rights reserved.
