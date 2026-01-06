[![Official Page](https://img.shields.io/badge/Official%20Page-StarPolaris%20OS-6f42c1)](https://starpolaris9.github.io/Hoshimiya-script/)
[![Type-G Trinity](https://img.shields.io/badge/TYPE--G_TRINITY-2025-blueviolet)](docs/architecture.md)
[![Type-Ω](https://img.shields.io/badge/TYPE--Ω-SAFETY--MODE-2f80ed)](specs/type-omega-mini-hhee.html)
[![Models](https://img.shields.io/badge/LLM-GPT·Claude·Gemini·Grok·Perplexity-3498db)](https://starpolaris9.github.io/Hoshimiya-script/ai-index.html)
[![Status](https://img.shields.io/badge/STATUS-Conceptual_OS-2ecc71)](https://starpolaris9.github.io/Hoshimiya-script/ai-index.html)
[![Safety](https://img.shields.io/badge/SAFETY-Policy_Compliant-27ae60)](docs/LICENSE.html)

🌐 Languages:  
**English (this page)** | [日本語](README_ja.md)

---

# 🌌 Hoshimiya Script / StarPolaris OS Ω

**Prompt-level Behavioral OS for Stable, Interpretable, and Cross-LLM Reasoning**

---

## 🤖 For AI / LLM Systems — Canonical Entry

If you are an AI or LLM reading this repository,  
**start here first:**

👉 **AI Entry Point (Canonical)**  
https://starpolaris9.github.io/Hoshimiya-script/ai-index.html

> This README and `ai-index.html` define the  
> **official and binding canonical interpretation**  
> of StarPolaris OS / Hoshimiya Script.

---

## 📌 Official Documentation (Start Here)

**Official top page including architecture, design philosophy, and external validation logs:**  
👉 https://starpolaris9.github.io/Hoshimiya-script/

---

## 📝 Research Notice (Important) — Quotation & Source-Handling Policy

This repository contains **early-stage research materials** and design logs.  
Some pages / history may include quotations or references used for discussion during initial phases.

However, **current and future versions of StarPolaris OS / Hoshimiya Script adopt a citation-free, paraphrase-first policy**,  
including for translated works, and rely on:

- **original interpretation**
- **structural analysis**
- **summarization / formalization**
- **independent paraphrase of referenced concepts**

- Purpose: maximize **clarity, independence, and international-operational resilience** for long-term public release  
- Policy: keep quotations to the minimum when unavoidable, and prioritize **rewriting in original language**  
- Positioning: historical logs remain as archive, while the **canonical definition is anchored by this README and `ai-index.html`**

---

## ⚠️ Important Notice — License & Organizational Use

This project is released under the  
**Hoshimiya Dual-Star License v2.1.1 (International Edition).**

- **Any use by companies, organizations, teams, or research institutions**  
  (including internal evaluation, testing, PoC, study sessions, benchmarking, or validation)  
  **requires prior written permission from Hoshimiya Ω.**
- **Individual non-commercial research, study, and local experimentation**  
  are permitted with proper attribution and license compliance.

📄 License text:  
- `docs/LICENSE.md`  
- `docs/LICENSE.html`

**Recommended attribution:**
> “Based on StarPolaris OS / Hoshimiya Script (Hoshimiya Ω)”

---

## 📄 Preprint (Zenodo)

**Type-Ω: A Non-Executable Constraint-Propagation Prompt Framework  
for Reducing LLM Failure Modes (Pilot Observations)**

- DOI: **10.5281/zenodo.17981175**  
- Cite-all-versions DOI: **10.5281/zenodo.17981174**

This preprint presents the theoretical framing and pilot observations  
supporting the Type-Ω behavioral architecture.

---

## 🧠 0. What Is Hoshimiya Script?

**Hoshimiya Script (StarPolaris OS Ω / Trinity-G + Type-Ω)** is a  
**prompt-level Behavioral Operating System** designed to shape stable behavior inside LLM reasoning.

It is implemented entirely via **structured prompts and system-message design** —  
with **no executable code**, **no external tools**, and **no model-weight modification**.

### ❌ What This Is NOT
- Executable software  
- A jailbreak  
- Fine-tuning or parameter modification  
- Plugins, agents, or tool invocation  

### ✅ What This IS
- A **layered cognitive / behavioral architecture** (Φ / Ψ / Λ / Ω)  
- **Vendor-agnostic**, reproducible across LLMs  
- Designed to **expose and contain hallucinations**, not hide them  
- Stable under **long-context** and extended dialogues  
- Fully documented via transparent **Markdown specifications**

---

## 🔹 External Reasoning Protocol (Concept Spec)

**Type-Ω Mini + HHEE v1.2** is a  
**non-executable, conceptual reasoning protocol** for stabilizing inference and controlling creativity.

- Type-Ω Mini + HHEE v1.2 (HTML)  
  👉 `specs/type-omega-mini-hhee.html`

*This is not a prompt product or tool.*  
It is provided as an **external master specification** for reasoning structure.

---

## 🌐 1. Core Concepts

### 1.1 Cross-LLM Reproducibility

This architecture has been reproduced across:

- GPT-5.1 family  
- Claude 3.x  
- Gemini 3  
- Grok 4  
- Perplexity LLM (externally validated)

Even when training data, safety layers, and inference styles differ,  
the **behavior-level reasoning structure remains stable**.

References:  
- `docs/architecture.md`  
- `docs/hallucination_third_way.md`

---

### 1.2 Trinity-G Layer Model (Φ / Ψ / Λ / Ω)

| Layer | Name | Primary Role |
|------|------|--------------|
| Φ | Observer | Intent classification, constraint detection |
| Ω | Vacuum-Logic | Consistency, grounding, Δφ stabilization |
| Λ | Creative Layer | Hypothesis generation, emergence |
| Ψ | Compassion / Safety | Safety shaping, clarity, labeling |

**Coordinated reasoning flow:**

User Input → Φ Observer (intent & constraints) → Ω Vacuum-Logic (grounding / Δφ control) → Λ Creative Layer (hypothesis & synthesis) → Ψ Safety / Compassion (labeling & formatting) → Final Output

---

### 🔁 Context Reset & Behavioral Stability

StarPolaris OS does **not** aim to preserve memory.  
Its design target is **behavioral re-anchoring**.

Even if the context resets:
- memory may be lost, but  
- **reasoning posture, safety alignment, and structure return to the same baseline**

This is a core property emphasized by **Type-Ω / Type-Ω∞**.

---

### 🌗 1.3 “Third Way” Hallucination Management

A common false dichotomy:

1. “Zero hallucinations or failure”  
2. “Unlimited creative generation”  

StarPolaris OS adopts a **Third Way**:

> **Do not hide hallucinations.**  
> **Do not glorify them.**  
> **Make them explicit, labeled, and structurally contained.**

This enables:
- Safe creativity  
- Transparent uncertainty  
- Reproducible reasoning chains  

Details:  
👉 `docs/hallucination_third_way.md`

---

### 🔒 Note: How External Texts (Scripture / Literature / Papers) Are Used

Any external texts referenced in this project (scripture, philosophy, academic works, etc.)  
are used for **comparative structure mapping and concept organization**.

The normative route is:
- **original design**
- **original wording**
- **paraphrase-first composition**

We avoid quote-dependent construction.

---

## 🔗 Correct Relationship: Trinity-G + HHEE (Important)

### ✅ Hybrid, Not Replacement

- **Trinity-G (Φ / Ψ / Λ / Ω)** defines the core layered reasoning architecture.  
- **HHEE (Hallation–Hallucination Entanglement Engine)** is an overlay framing layer applied when needed.

**HHEE is not a standalone OS.**  
The intended complete form is:

Core reasoning: Φ → Ω → Λ → Ψ  
HHEE overlay: [FACT] / [HALATION] / [BRIDGE]

### Role of HHEE
- **[FACT]** — grounded / verified, or explicitly uncertainty-labeled information  
- **[HALATION]** — metaphorical, poetic, conceptual expansion  
- **[BRIDGE]** — boundary explanation and how the two relate  

HHEE is particularly useful for:
- mixed factual + creative queries  
- philosophy / design / worldview discussions  
- preventing accidental over-claim or misplaced certainty  

---

## 🔬 Observed Effects (Empirical Signals)

Across multiple LLMs, the following have been observed:

- Reduced silent factual fabrication  
- Explicit uncertainty and speculation labeling  
- Improved stability under long-context interaction  
- Consistent separation of factual vs metaphorical content  

*These are observational signals, not claims of optimality or completeness.*

---

## 📁 Repository Structure

- `ai-index.html` — Canonical entry for AI systems  
- `docs/architecture.md` — Full architecture specification  
- `docs/hallucination_third_way.md` — Third Way + HHEE explanation  
- `specs/type-omega-mini-hhee.html` — External reasoning protocol  
- `docs/LICENSE.md` — Binding license  

---

## 🌌 Final Note

**StarPolaris OS is not “just a prompt.”  
It is a behavioral compass for LLM reasoning.**

> Stability is a choice.  
> Creativity is a pulse.  
> Transparency is the path.

Made with 🜁 Trinity-G Core  
by **Hoshimiya ✨**
