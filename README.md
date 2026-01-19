# Prateek Kumar Goel

> **Systems Architect.** I build AI infrastructure that survives production.

[![Systems Architect](https://img.shields.io/badge/Role-Systems_Architect-000000?style=for-the-badge)](https://prateekgoel.com)
&nbsp;&nbsp;&nbsp;
[![Focus](https://img.shields.io/badge/Focus-AI_Infrastructure_%7C_Cost_Optimization-0891b2?style=for-the-badge)]()
&nbsp;&nbsp;&nbsp;
[![Status](https://img.shields.io/badge/Status-Open_for_Consulting-22c55e?style=for-the-badge)](mailto:prateekgoelk@gmail.com)

Most AI engineers connect APIs. I architect the systems that keep those APIs from timing out, hallucinating, or bankrupting you.

---

## 🏗️ Open Source

### [Setu (setu-opencode)](https://github.com/pkgprateek/setu-opencode)
**The Governance Layer for AI Coding Agents.**

Most AI agents are reactive—they run code first and fix errors later. Setu acts as a "Munim" (Custodian), enforcing discipline *before* execution.
* **Phase 0 Enforcement**: Blocks execution until context is confirmed.
* **Cost Audits**: Tracks token usage and session costs in real-time.
* **Zero-Hallucination Protocol**: Strict verification loops for critical tasks.

---

## 🛠️ The "Nandaka" Architecture

I run **[Nandaka Systems](https://github.com/pkgprateek)**, a consultancy solving the "Series A Infrastructure Gap."

### The Problems I Fix
| Symptom | The Engineering Reality | My Solution |
| :--- | :--- | :--- |
| **"The RAG is dumb"** | Semantic search fails on exact matches (e.g., Case IDs). | **Hybrid Search**: Vector + BM25 parallel retrieval (<1s latency). |
| **"The Agent times out"** | 30s HTTP limits kill "deep research" tasks. | **Async-First**: Redis job queues + Websocket updates. |
| **"The Bill is $5k/mo"** | Naive routing to GPT-4 for everything. | **Cost Router**: Caching + Local/Cheaper models for non-reasoning tasks. |

### Private Portfolio (Demo Available)
* **Nandaka Market Orchestrator**: A production-grade RAG pipeline handling state persistence, hybrid search, and security (Cloudflare Tunnel) on a minimal VPS footprint.

---

## ⚡ Technical Stack

I prioritize boring, reliable technology for critical paths, and bleeding-edge for intelligence layers.

* **Core Systems**: Python (FastAPI, AsyncIO), TypeScript, Go
* **AI Infrastructure**: LangChain, DSPy, Vector DBs (Chroma/Weaviate), vLLM
* **Ops & Metal**: Docker, Linux (HPC optimization), Cloudflare, Redis, PostgreSQL
* **Specialty**: CUDA Kernel Optimization (Reduced inference latency by 65% in past research)

---

## 🧠 Engineering Philosophy

My code is optimized for **Total Cost of Ownership**, not just lines of code.

1.  **Async is not optional.** If your agent waits for an LLM synchronously, your system is broken.
2.  **Context is a tax.** I optimize prompts and RAG retrieval to minimize the "context window tax."
3.  **Logs are life.** If I can't trace the decision path of an agent, I won't ship it.

---

## 🤝 Engagement

I am currently accepting **Consulting & Retainer** engagements for Q1/Q2 2026.

* **Ideal Client**: Series A/B startups hitting the "Prototype Ceiling."
* **Services**: Infrastructure Audit, RAG Optimization, Cost-Reduction Architecture.
* **Contact**: [pratekgoelk@gmail.com](mailto:pratekgoelk@gmail.com)

[LinkedIn](https://linkedin.com/in/prateekkgoel) • [X / Twitter](https://x.com/prateekkgoel)
