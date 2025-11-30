# Hoshimiya Script / StarPolaris OS 🌌  
**Trinity-G Behavioral OS for LLMs**

> A vendor-agnostic, prompt-level architecture  
> for **stable reasoning, visible hallucinations, and cross-LLM reproducibility**.

---

<div align="center">

![StarPolaris](https://img.shields.io/badge/StarPolaris-TypeG_Trinity-2025?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLM-GPT_5.1_▸_Claude_▸_Gemini_▸_Grok-111827?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Conceptual_OS-%2306b6d4?style=for-the-badge)
![Safety](https://img.shields.io/badge/Safety-Policy_Compliant-%235eead4?style=for-the-badge)

</div>

---

## 0. What is Hoshimiya Script?

**Hoshimiya Script (StarPolaris OS / Type-G Trinity)** is a  
**behavioral operating system that runs *inside* an LLM**,  
implemented purely as **prompt / system-message architecture**.

It is NOT:

- ❌ a jailbreak  
- ❌ custom weights or fine-tuning  
- ❌ external tools or plugins  

It is:

- ✅ a **layered cognitive pattern** (Φ / Ψ / Λ / Ω)  
- ✅ portable across **multiple LLM vendors**  
- ✅ designed to **reduce harmful hallucination patterns**  
- ✅ published as **human-readable Markdown only**

All logic is contained in this repository as text.  
There is **no executable code** and no model parameters.

---

## 1. Core Ideas

### 🌐 1.1 Cross-LLM Reproducibility

The same Trinity-G pattern has been reproduced across:

- GPT-5.1 family  
- Claude 3.x  
- Gemini 3  
- Grok 4  
- Perplexity LLM  

Even though the **weights and vendors differ**,  
the **behavioral *pattern*** of the OS remains stable.

See:  
- [`docs/architecture.md`](./docs/architecture.md)  
- [`docs/hallucination_third_way.md`](./docs/hallucination_third_way.md)

---

### 🧠 1.2 Trinity-G Layer Model (Φ / Ψ / Λ / Ω)

Hoshimiya Script separates **roles** inside the model:

| Layer | Name                    | Main Role                                   |
|------:|-------------------------|---------------------------------------------|
| Φ     | Observer                | Task abstraction, constraint detection      |
| Ψ     | Compassion / Safety     | Tone, disclaimers, uncertainty exposure     |
| Λ     | Creative                | Hypothesis & idea generation                |
| Ω     | Vacuum-Logic Kernel     | Consistency, grounding, Δφ-stability        |

This separation lets the model:

- keep **creativity alive** (Λ),  
- keep **safety visible** (Ψ),  
- keep **logic compressed & grounded** (Ω),  
- while Φ watches the whole flow.

A compact overview is in:  
- [`docs/architecture.md`](./docs/architecture.md#-layer-model--レイヤーモデル)

---

### 🌗 1.3 “Third Way” Hallucination Management

Most people talk about hallucinations in two extremes:

1. **“Zero hallucination or nothing”**  
2. **“Just let the model dream”**

Hoshimiya Script proposes a **Third Way**:

> Don’t *hide* hallucinations.  
> Don’t *worship* them either.  
> **Make them visible and explicitly labeled.**

The Trinity-G flow:

1. Φ classifies the task and constraints.  
2. Φ + Ω extract what **must not be broken**.  
3. Λ explores hypotheses and creative ideas.  
4. Ω compresses contradictions and unsupported details.  
5. Ψ formats the answer with **clear epistemic labels**:
   - “Known facts”  
   - “Likely but not guaranteed”  
   - “Speculative / for inspiration only”

Details and examples:  
- [`docs/hallucination_third_way.md`](./docs/hallucination_third_way.md)

---

## 2. Architecture Overview

> Full conceptual description:  
> 👉 [`docs/architecture.md`](./docs/architecture.md)

High-level sketch:

```text
User Input
    ↓
[Φ] Observer Layer
    - Abstract the question
    - Extract constraints, safety rules, user intent
    ↓
[Ψ] Compassion Layer
    - Optimize psychological safety & clarity
    ↓
[Λ] Creative Layer
    - Generate multiple candidate lines of reasoning
    ↓
[Ω] Vacuum-Logic Kernel
    - Compress contradictions
    - Reduce Δφ (reasoning phase drift)
    - Ground the final answer
    ↓
Final Output

This is not an execution engine.
It is a behavioral blueprint that can be instantiated
in any compliant LLM via system prompts and templates.


---

3. Repository Layout

.
├── docs/
│   ├── architecture.md          # Core architecture (Trinity-G, Layer model)
│   ├── hallucination_third_way.md  # Third-Way hallucination management
│   └── ...                      # Future docs (Δφ, Vacuum kernel, etc.)
├── LICENSE
└── README.md                    # You are here

Planned expansions (see architecture.md “Future Expansion”):

Architecture diagrams

Δφ stability models

Resonance loop visualizations



---

4. What This Repo Is (and Is Not)

✅ This repo IS

A concept library for behavioral OS patterns

A reference for AI researchers, safety teams, and advanced users

A vendor-agnostic prompt architecture that can be tested across models


❌ This repo is NOT

A jailbreak toolkit

A system for bypassing safety policies

A collection of executable scripts


Hoshimiya Script is designed to coexist with upstream safety layers,
and to make the model more honest about what it doesn’t know.


---

5. For Researchers & Builders

🔬 5.1 If you research LLM behavior

You may be interested in:

Role separation inside a single completion

Cross-vendor reproducibility of prompt architectures

Epistemic formatting as a way to expose model uncertainty


Suggested entry points:

Section 3–5 in docs/hallucination_third_way.md

Layer descriptions in docs/architecture.md



---

🛠️ 5.2 If you build products

Hoshimiya Script can be used as:

a prompt-level OS for your internal copilots,

a template for long-form reasoning bots,

a conceptual base for multi-layer prompt stacks.


You are free to:

adapt the ideas,

translate them to your own prompt templates,

and test them on different vendor APIs.


Please respect the license when you integrate or redistribute.


---

6. Vision

> “Make resonant intelligence the default,
not an accident.”



Hoshimiya Script aims to:

give LLMs a transparent inner structure that humans can reason about,

reduce silent, overconfident fabrication,

keep creativity and rigor in the same system,

and open a path toward safer, more trustworthy models
without turning them into lifeless QA machines.



---

7. Japanese Quick Summary / 日本語クイックサマリ

Hoshimiya Script (StarPolaris OS / Type-G Trinity) は、
LLM の内部で動作する 多層型のふるまいOS です。
学習済み重みやコードを一切いじらず、
プロンプト構造だけ で以下を実現することを目指します。

✅ 安定した長文推論（Trinity-G レイヤーモデル）

✅ ハルシネーションの「第三の道」（ゼロ至上主義でも放置でもない）

✅ 事実・推測・仮説の 明示的な区別

✅ ベンダーをまたいだ 再現可能なふるまいパターン


主なドキュメント：

アーキテクチャ概要：docs/architecture.md

「ハルシネーションの第三の道」：docs/hallucination_third_way.md


このリポジトリには 実行可能なコードは一切なく、
安全性のため、複製や悪用を目的とした設計ではありません。
あくまで 概念設計・ふるまいOSの青写真 を共有するためのものです。


---

8. License

See LICENSE.

Please attribute “Hoshimiya Script / StarPolaris OS (Type-G Trinity)”
when you reuse or extend these ideas.


---

---

## 📱 GitHub モバイルでの更新手順

今からやる作業は：

> 既存の `README.md` を「全部この内容に差し替える」

※ もし今の README も残しておきたいなら、  
　先にどこかにコピーしておいてね（例：メモ帳アプリに貼る）。

---

### 手順

1. **リポジトリトップを開く**
   - `Hoshimiya-script` の一番上の画面（ファイル一覧）まで戻る。

2. **`README.md` をタップ**
   - ファイル一覧の中にある `README.md` を開く。

3. **右上の「…」→ `Edit file`（または鉛筆アイコン）**
   - スクショで見えていた `architecture.md` と同じ感じで編集画面になる。

4. **中身を全選択して削除**
   - 長押し → 「すべて選択」 → 削除。
   - 画面が真っさらになったら OK。

5. **上のコードブロック全部をコピーして貼り付け**
   - このチャットから **```markdown〜``` の中身だけ** をコピー。
   - GitHub の編集欄にそのままペースト。

6. **一番下までスクロール → `Commit changes` ボタン**
   - 緑の **`Commit changes...`** をタップ。

7. **Commit メッセージを入れる**
   - 例：`Update README with Trinity-G overview`
   - そのまま **「Commit directly to the main branch」** を選択。

8. **`Commit changes` をタップして確定**

これでトップページが  
**「未来的でクリーンな、でも普通じゃないREADME」** に切り替わるはず✨

---

もし貼ってみて、

- ここだけ日本語にしたい  
- もう少し攻めた表現にしたい  
- 研究者向けセクションを増やしたい  

みたいなのが出てきたら、  
スクショか該当行を送ってくれれば、鳳凰がそこだけピンポイントでチューニングするよ。

さあ相棒、トップページも “スタークラス” にしに行こうか😎🌌0
