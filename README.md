🌐 Languages:  
[English](README.md) | [日本語](README_ja.md)

---

# 🌌 Hoshimiya Script / StarPolaris OS

**Hoshimiya Script (StarPolaris OS / Trinity-G + Type-Ω)**  
is a **prompt-level cognitive architecture** that functions as a  
**behavioral stability operating system for large language models**.

It is designed to maintain **coherent reasoning, uncertainty control,  
and behavioral consistency** across **long-horizon dialogue**,  
including scenarios where conversations approach or reset due to context length limits.

This repository documents the **architecture, design rationale, and reproducible behavior**  
of a **non-executable, model-agnostic cognitive OS**.

---

## 🚀 Official Project Page — Full Specification & Evaluation

> **This README is intentionally dense and incomplete.**  
> It serves as a technical index, not the full explanation.

> **For architecture diagrams, structured specifications,  
> cross-model evaluation logs, and conceptual grounding,  
> refer to the official project page:**

👉 **https://starpolaris9.github.io/Hoshimiya-script/**

> 🇯🇵 **日本語の方へ**  
> 全体像・思想・構造を理解したい場合は、  
> READMEを読み進める前に上記トップページを先に見てください。

---

## ⚖️ License & Usage Constraints (Read Carefully)

This project is released under the  
**Hoshimiya Dual-Star License v2.1.1 (International Edition)**.

**Summary (non-exhaustive):**

- ✅ **Individual, non-commercial** research, study, education, and commentary  
  are permitted **with proper attribution**.
- ❌ **Any organizational use** — including companies, labs, research groups,  
  internal evaluation, testing, workshops, or internal knowledge sharing —  
  **requires prior written permission from Hoshimiya Ω**,  
  regardless of commercial intent.
- ❌ **Commercial use** is prohibited without explicit authorization.

📄 Full legal text (authoritative):  
👉 `docs/LICENSE.html` / `docs/LICENSE.md`

Attribution format (when applicable):  
> “Based on StarPolaris OS / Hoshimiya Script (Hoshimiya Ω).”

---

![Type-G Trinity](https://img.shields.io/badge/TYPE--G-TRINITY--2025-9b59b6)
![Type-Ω](https://img.shields.io/badge/TYPE--Ω-SAFETY--MODE-2f80ed)
![Models](https://img.shields.io/badge/LLM-GPT·Claude·Gemini·Grok·Perplexity-3498db)
![Status](https://img.shields.io/badge/STATUS-CONCEPTUAL%20OS-2ecc71)
![Safety](https://img.shields.io/badge/SAFETY-POLICY%20COMPLIANT-27ae60)

---

<div align="center">

![StarPolaris](https://img.shields.io/badge/StarPolaris-TypeG_Ω_Trinity_2025-blueviolet?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLM-GPT_5.1・Claude・Gemini・Grok・Perplexity-111827?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Conceptual_OS-23b06d?style=for-the-badge)
![Safety](https://img.shields.io/badge/Safety-Policy_Compliant-25eaa2?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/StarPolaris9/Hoshimiya-script?color=blueviolet&style=for-the-badge)
![License](https://img.shields.io/github/license/StarPolaris9/Hoshimiya-script?color=brightgreen&style=for-the-badge)

</div>

---

## 0. What is Hoshimiya Script?

Hoshimiya Script is a **behavioral operating system for LLM reasoning**,  
implemented entirely at the **prompt and interaction-structure level**.

It does **not** rely on:

- ❌ jailbreak techniques  
- ❌ fine-tuning or weight modification  
- ❌ plugins, tools, or external code  

Instead, it provides:

- ✅ a **layered cognitive control model** (**Φ / Ψ / Λ / Ω**)  
- ✅ **cross-LLM portability** without model-specific adaptation  
- ✅ explicit handling of **hallucination visibility and containment**  
- ✅ **behavioral stability under extended or fragmented context**  
- ✅ fully transparent, auditable **Markdown-based documentation**

This repository contains **no executable code**  
and **no model parameters**.
