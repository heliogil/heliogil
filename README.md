<h1 align="center">Hélio Gil</h1>

<p align="center">
  <b>AI Builder · Venture Studio · Founder</b><br/>
  Building products and infrastructure with autonomous AI agents.
</p>

---

## What I'm building

### 🦓 Zebra Shield (formerly SharpAnalysis)
*Sports betting bankroll management — discipline over predictions.*

SaaS with bankroll tracking, Kelly criterion sizing, Discipline Score, and a bankroll
intelligence engine. ML pipeline (XGBoost, Brier 0.21) runs as R&D tier.
Stack: FastAPI, PostgreSQL, Jinja2, Stripe, MiniMax M3.
→ *Private repo (product in market)*

---

### 🖥️ FPSReal — [github.com/heliogil/fpsreal](https://github.com/heliogil/fpsreal)
*Brazil's first PC hardware comparator ranked by cost-per-FPS.*

Scrapes KaBuM, Pichau, Terabyte and Mercado Livre. Normalizes prices + benchmarks.
Auto-generates content from anomalies in the data.
Stack: Next.js 14, FastAPI, PostgreSQL, Playwright, Three.js (3D viewer).
→ *In active development (Sprint 1)*

---

### 🤖 Hermes Factory — [showcase](https://github.com/heliogil/hermes-factory-showcase)
*Multi-agent AI factory running on a VPS.*

Production factory processing task packets through ephemeral Docker executors.
Agents: Ergon (builder), Argus (reviewer), Hermes (orchestrator), Caliope (strategist), MKT pair.
Patterns: multi-pass execution, TDD enforcement, auto-reassignment, metrics ledger.
Stack: MiniMax M3, Docker, bash, Python, paramiko.

---

### 🧠 Jarvis — [showcase](https://github.com/heliogil/jarvis-showcase)
*Personal AI assistant on Discord.*

Deterministic intent routing → grounding (live facts before LLM) → MiniMax M3 with tools.
Capabilities: voice (Whisper), vision, deep work packets, daily briefings, VPS diagnostics via SSH.
Stack: Python, Discord.py, MiniMax M3, Whisper, FastAPI, SQLite FTS5.

---

## Infrastructure philosophy

Everything runs on a single VPS. No per-token API costs — MiniMax M3 flat-rate subscription.
Factory processes ~150 tasks/60 days. First-pass success rate tracked via ledger.

```
VPS (8 cores, 24 GiB RAM)
 ├─ sharpanalysis API     (FastAPI + uvicorn, systemd)
 ├─ hermes-factory        (6 agents, cron-driven, ephemeral Docker executors)
 ├─ jarvis                (4 containers: discord, scheduler, api, whisper)
 ├─ nerve center          (internal dashboard, nginx + LoginGate)
 └─ postiz                (social media scheduling)
```

## Stack

`Python` `FastAPI` `PostgreSQL` `Next.js` `TypeScript` `Docker` `MiniMax M3`
`XGBoost` `Playwright` `Stripe` `paramiko` `SQLite FTS5` `Alembic` `Tailwind`

---

<p align="center">
  <a href="mailto:heliogil@gmail.com">heliogil@gmail.com</a>
</p>
