<div align="center">

# Rob Savage

**Senior Software Engineer building sports analytics, agent infrastructure, Bayesian research tools, and personal automation.**

San Diego native in Portland, OR. Personal projects here are independent of my employer.

*Sports analytics · Agentic AI systems · Bayesian modeling · Knowledge/retrieval infrastructure · Cloud FinOps*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/robsavage/)
[![Email](https://img.shields.io/badge/rob.savage%40me.com-000000?style=for-the-badge&logo=apple&logoColor=white)](mailto:rob.savage@me.com)
[![Open to Work](https://img.shields.io/badge/%F0%9F%91%80%20Open%20to%20Sports%20Analytics%20Roles-238636?style=for-the-badge)](https://www.linkedin.com/in/robsavage/)

*Senior Software Engineer · Nike · Portland, OR*

</div>

---

## 🧠 savage-vault-showcase

**[Obsidian vault architecture for coding agents →](https://github.com/robsavage619/savage-vault-showcase)**

A sanitized look at the knowledge system behind my local coding and research workflow. The real vault stays private; this repo shows the structure — routing docs, retrieval packs, review metadata, project manifests, validation checks, and redacted examples.

| | |
|---|---|
| **Corpus behind it** | 1,088 wiki pages · 587 source summaries · 312 concept cards · 117 book hubs · 18 project manifests |
| **What it solves** | Gets Codex, Claude Code, and ChatGPT-style agents from a vague request to the right pack, source note, or project manifest without searching the whole vault |
| **Agent contract** | The vault gives context; the live repo/source still wins. Agents are routed to inspect current files before changing code or making live-state claims. |
| **Ingestion depth** | Books and papers become hubs, extraction notes, targeted chapter notes, concept cards, and route wiring — only where that extra grain changes the agent's behavior |
| **Boundary** | The showcase publishes the operating model, not the library: no raw PDFs, books, personal notes, or full third-party-derived summaries |
| **Stack** | Obsidian · Claude Code · Codex · Markdown · Mermaid · Python validation · GitHub Actions |

---

## 🏈 sleeper-fantasy-football-manager

**[AI dynasty fantasy football GM →](https://github.com/robsavage619/sleeper-fantasy-football-manager)**

A full-stack AI general manager that re-computes player values under league-specific scoring, compares them to generic PPR baselines, and ranks trade targets by roster context.

| | |
|---|---|
| **Valuation** | Re-scores every player under the league's exact settings *and* generic PPR; ranks the mispricing created by custom passing and yardage bonuses |
| **Market signals** | Monte-Carlo title equity, buyer/seller contention windows, TD-regression buy-low/sell-high, owner behavioral profiling learned from the league's real trade history |
| **Matchup Lab** | Pre-lock win probability, stadium/weather splits, playoff strength-of-schedule, snap-share wire early-warning, handcuff/leverage map |
| **AI loop** | Deterministic engines build one briefing → Claude Code reasons, self-critiques, and posts back → UI renders. No runtime LLM key in the backend. |
| **Stack** | Python 3.12 · Polars · FastAPI · React 19 · TypeScript 6 · Vite 8 · Tailwind 4 · nflverse · Claude Code · 32 engines · 210 tests |

---

## ⚾ savage-trade-evaluator

**[MLB front-office trade evaluation platform →](https://github.com/robsavage619/savage-trade-evaluator)**

Built to answer one question: *Was this trade a good move for this team, in this contention window, under this front office?*

| | |
|---|---|
| **Data** | 1.29M+ rows · transactions 1880–2024 · Statcast percentiles & arsenal · Spotrac $49B contracts · front-office personnel |
| **War Room** | Deadline command center: buyer/seller verdict, CBT headroom, roster holes, 3-year payroll projection |
| **AI Brief** | Structured-output GM brief: highest-leverage move today, trade packages with two-sided surplus accounting, counterparty leverage reads |
| **Research** | 35 rounds. Original thesis empirically rejected and reported. Four validated findings including sell-high skill and K%-trajectory signal. |
| **Stack** | Python 3.12 · DuckDB · PyMC (Bayesian) · FastAPI · React 19 · TypeScript 6 · Vite 8 · Tailwind 4 · model2vec RAG |

---

## 📈 cortex

**[Quantitative research platform →](https://github.com/robsavage619/cortex)**

As of the latest run, no factor clears the significance bar, so live trading is disabled.

| | |
|---|---|
| **Factors** | Momentum · Low-vol · Sharpe · Value · Quality — all point-in-time, zero lookahead |
| **Alt-data** | SEC EDGAR Form 4 · 13F institutional flow · Senate congressional trades · White House executive mentions |
| **Rigor** | Pre-registered backtest harness · Newey-West HAC t-stats · multiple-testing correction · long-short spread |
| **Calibration** | Brier score · per-conviction hit-rate buckets · reliability diagrams on every thesis |
| **Stack** | Python 3.12 · DuckDB + HNSW vector search · fastembed (local) · FastAPI · React 18 · Vite |

---

## 🏋️ savage-labs

**[Personal performance platform →](https://github.com/robsavage619/savage-labs)**

WHOOP + Apple Health + Hevy + DUPR fused through a single typed `DailyState` for readiness, training load, and workout planning.

| | |
|---|---|
| **Signals** | Drug-adjusted HRV (σ-deviation, medication-aware weights) · Gabbett ACWR from fused strain + tonnage |
| **Gate engine** | 20 hard rules derived from physiology research. Claude proposes the plan; deterministic gates accept or reject it. |
| **Science** | Banister CTL/ATL/TSB · concurrent training interference (pickleball-primary) · pre-registered N-of-1 hypothesis catalog |
| **Stack** | Python 3.12 · FastAPI · DuckDB · Next.js 15 · React 19 · Tailwind v4 OKLCH · Claude Opus 4.7 |

---

## 🧪 agent-eval-kit

**[LLM regression-detection harness →](https://github.com/robsavage619/agent-eval-kit)** · MIT · Published on PyPI

```sh
uv add agent-eval-kit
```

Three judge types · exact match · numeric tolerance · LLM-as-judge (~$0.001/case) · regression diffing across prompt versions · per-run latency + cost tracking · JUnit XML for CI · Markdown for PR comments

---

## 🏟️ xfriars

**[San Diego Padres analytics engine →](https://github.com/robsavage619/xfriars)** · Powers [@xFriars](https://x.com/xFriars) on X

| | |
|---|---|
| **Data** | MLB Stats API · Statcast leaderboards · full franchise history · team and player profiles |
| **Engine** | Deterministic SQL detectors, interest-weight scoring, `pad` CLI driving the full pipeline |
| **Output** | Branded stat cards rendered to PNG via D3, auto-posted to X |
| **Stack** | Python 3.12 · DuckDB · React 19 · TypeScript · D3.js · Jinja2 |

---

## Stack

![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PyMC](https://img.shields.io/badge/PyMC_Bayesian-E97627?style=flat-square)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-111827?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B5563?style=flat-square)
![Claude API](https://img.shields.io/badge/Claude_API-CC785C?style=flat-square)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=astral&logoColor=white)

<div align="center">

<br/>

</div>
