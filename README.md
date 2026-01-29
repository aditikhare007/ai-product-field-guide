# 🧭 AI Product Field Guide

## 👩‍💻 Author — Aditi Khare  
Writing on AI research, product thinking, and system architecture  

🌐 **Website:** [aditikhare.com](https://aditikhare.com)  
🔗 **GitHub:** [AI Product Field Guide](https://github.com/aditikhare007/ai-product-field-guide/)  
🤗 **Hugging Face:** [AditiShashiKhare](https://huggingface.co/AditiShashiKhare)  
💼 **LinkedIn:** [Aditi Khare](https://www.linkedin.com/in/aditikhare)  

---

**Notes from the field on building AI products that don’t fall apart in production.**

This repository is a practical field guide to designing **GenAI**, **Agentic AI**, and **Model Context Protocol (MCP)**–based products — with a sharp focus on **reliability, evaluation, and system-level failure modes**.

Not demos.  
Not prompt hacks.  
Not hype.

⭐ Star this repo if you’re building real AI products beyond the prototype phase.

---

## Why This Guide Exists

Most AI products don’t fail because the model is bad.

They fail because:
- prompts silently degrade over time  
- agents loop, drift, or misuse tools  
- RAG systems retrieve data but still answer incorrectly  
- context grows until it becomes noise  
- evaluation relies on intuition instead of signals  

This guide exists to help teams avoid the **most common — and most expensive — AI product failures**.

---

## 🧭 Products Index (Start Here)

Each product below is a **self-contained product note**.  
All links work both on **GitHub** and **GitHub Pages**.

---

### 🧠 GenAI Foundations

1. **[Prompt Evaluation Engine (When You Have No Labels)](products/01-prompt-eval-engine/)**  
   Estimating prompt reliability when ground truth does not exist.

2. **[Context Compression Playbook](products/02-context-compression/)**  
   Reducing context size while preserving task-critical signal.

3. **[Why RAG Systems Fail (A Practical Taxonomy)](products/03-rag-failure-taxonomy/)**  
   Understanding retrieval, context, and answer-synthesis failure modes.

---

### 🤖 Agentic AI

4. **[Agent Reliability Scorecard (What Breaks First)](products/04-agent-reliability-scorecard/)**  
   A structured way to evaluate agent behavior, retries, and drift.

5. **[Tool-Calling Failure Simulator (Conceptual)](products/05-tool-calling-failure-sim/)**  
   Designing agents that behave predictably when tools partially or silently fail.

---

### 🔌 Model Context Protocol (MCP)

6. **[MCP Mental Model for Product Teams](products/06-mcp-mental-model/)**  
   A plain-language explanation of what MCP changes — and when it doesn’t.

7. **[MCP-First AI Product Architecture](products/07-mcp-first-architecture/)**  
   High-level architectural patterns for MCP-based AI products.

---

## When This Guide Is Useful

This repository is especially useful if:

- your prompts worked last week but not anymore  
- your agent behaves well in demos but not in production  
- your RAG system looks correct but answers incorrectly  
- your context window keeps growing without improving outcomes  
- MCP feels promising but unclear  

If none of these resonate, this guide may not be for you.

---

## What This Repo Is

- A curated collection of **public-safe AI product designs**
- Focused on **failure modes, evaluation, and system boundaries**
- Written for builders, product leaders, and applied researchers
- README-first by design — clarity over code volume

Each entry is framed as an **AI product**, not an experiment.

---

## What This Repo Is Not

- Not a framework or SDK  
- Not end-to-end implementations  
- Not proprietary metrics or pipelines  
- Not agent hype or demo content  

Some details are intentionally excluded.  
That’s not an omission — it’s a boundary.

---

## Design Principles

> Most AI failures are **system failures**, not model failures.

This guide favors:
- evaluation over intuition  
- reliability over cleverness  
- system boundaries over monoliths  
- clarity over completeness  

---

## Status

- 🟢 Actively evolving  
- 🟡 Products added deliberately, not frequently  
- 🔒 Deeper implementations are intentionally excluded by design.

This repository shares **AI product insights only**.  
Advanced execution details and internal metrics are excluded by design.
