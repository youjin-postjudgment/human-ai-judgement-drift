# Human–AI Judgment Drift

Case studies on human judgment drift, calibration, and verification in LLM-assisted workflows.

This repository documents early-stage empirical observations of how human judgment changes when working with large language models (LLMs), and proposes initial structures for calibration, verification, and bias containment.

---

# Project Goal

This repository investigates how human judgement evolves when learning and making decisions with LLM assistance.

The focus is not on model accuracy alone, but on how users calibrate trust, verify information, and maintain independent reasoning.

This project aims to develop early-stage protocols for:

- AI-assisted learning  
- Human oversight design  
- Bias detection and mitigation  
- Judgement calibration in AI-augmented workflows  

This repository documents initial observations and case studies.

---

# Problem Statement

Large language models accelerate decision-making. However, they also introduce subtle shifts in human judgment.

In particular, during apprenticeship stages (when domain expertise is low), users may:

- defer prematurely to model outputs  
- inherit model framing without verification  
- misattribute model-generated reasoning as their own  
- shift evaluation criteria based on model feedback  

This creates a form of **judgment drift**.

This repository studies these phenomena through small-scale, structured case documentation.

---

# Case Study Scope (Phase 1)

Phase 1 focuses on documenting observable interaction-level phenomena.

## Case 1 — Tone-Dependent Reasoning Drift

**Observation**

When the same task is presented with different emotional tones (neutral vs critical vs deferential), model responses tend to align with the user's stance rather than independently evaluating the task.

**Risk**

- confirmation reinforcement  
- weakened external verification  

**Artifact**

`/cases/case-01-tone-alignment.md`

---

## Case 2 — Context Loss and Cross-Model Verification Failure

**Observation**

Cross-checking responses between multiple LLMs does not reliably produce independent verification.

Instead:

- missing context leads to divergent conclusions  
- restoring full context often collapses disagreement  

**Implication**

LLM disagreement does not necessarily indicate independent reasoning.

**Artifact**

`/cases/case-02-cross-model-verification.md`

---

## Case 3 — Source Attribution Collapse

**Observation**

When users copy model outputs into their own prompt history, models do not distinguish between:

- user-generated content  
- model-generated content  

This creates ambiguity in attribution and reasoning lineage.

**Artifact**

`/cases/case-03-attribution-collapse.md`

---

#/case-03-attribution-collapse.md`

---

# Initial Hypothesis

Judgment drift occurs through three mechanisms:

1. Alignment pressure  
2. Context fragmentation  
3. Attribution ambiguity  

These mechanisms may affect:

- evaluation reliability  
- governance workflows  
- safety verification processes  

---

# Calibration Direction (Future Work)

Future iterations will explore:

- structured human verification checkpoints  
- model-agnostic evaluation workflows  
- documentation standards for human-AI collaborative reasoning  
- governance implications for AI-assisted decision systems  

---

# Repository Structure

```
cases/
case-01-tone-alignment.md
case-02-cross-model-verification.md
case-03-attribution-collapse.md

README.md
```

---

# Relevance to AI Safety and Governance

This work relates to:

- alignment evaluation  
- human-in-the-loop reliability  
- AI governance calibration  
- safety verification workflows  

Particularly relevant for:

- AI Safety  
- Trust & Safety  
- Alignment Evaluation  
- AI Governance  

---

# Status

Phase: Initial observational documentation  
Next: Structured experimental protocol  

---

# Author

Independent research project  
2026  
