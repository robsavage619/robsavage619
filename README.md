<div align="center">

# Rob Savage

**I don't build dashboards. I build the thing you open when you actually need to make a call.**

San Diego native. Working at Nike. Building tools I'm proud of.

*Sports analytics · Agentic AI · Bayesian modeling · Cloud FinOps*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/robsavage/)
[![Email](https://img.shields.io/badge/rob.savage%40me.com-000000?style=for-the-badge&logo=apple&logoColor=white)](mailto:rob.savage@me.com)
[![Open to Work](https://img.shields.io/badge/%F0%9F%91%80%20Open%20to%20Sports%20Analytics%20Roles-238636?style=for-the-badge)](https://www.linkedin.com/in/robsavage/)

*Senior Software Engineer · Nike · Portland, OR*

</div>

---

## ⚾ savage-trade-evaluator

> *Most trade tools give every player the same price tag regardless of who's buying. That's wrong. A cost-controlled arm is a luxury to a rebuilder and a pennant to a contender two games up in August with a hole in the rotation.*

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

> *Most retail stock tools optimise for action — buy buttons, green arrows, dopamine. CORTEX optimises for the opposite: slower, better-calibrated decisions, and intellectual honesty about edge.*

**[Quantitative research platform →](https://github.com/robsavage619/cortex)**

As of the latest run, no factor clears the significance bar — so nothing trades live. That restraint is the point.

| | |
|---|---|
| **Factors** | Momentum · Low-vol · Sharpe · Value · Quality — all point-in-time, zero lookahead |
| **Alt-data** | SEC EDGAR Form 4 · 13F institutional flow · Senate congressional trades · White House executive mentions |
| **Rigor** | Pre-registered backtest harness · Newey-West HAC t-stats · multiple-testing correction · long-short spread |
| **Calibration** | Brier score · per-conviction hit-rate buckets · reliability diagrams on every thesis |
| **Stack** | Python 3.12 · DuckDB + HNSW vector search · fastembed (local) · FastAPI · React 18 · Vite |

---

## 🏋️ savage-labs

> *My WHOOP didn't know I'd taken a beta-blocker. My workout app had no idea how I slept. I got frustrated enough to build something.*

**[Personal performance platform →](https://github.com/robsavage619/savage-labs)**

WHOOP + Apple Health + Hevy + DUPR fused through a single typed `DailyState`. Not a wearable dashboard — a sports-science platform.

| | |
|---|---|
| **Signals** | Drug-adjusted HRV (σ-deviation, medication-aware weights) · Gabbett ACWR from fused strain + tonnage |
| **Gate engine** | 20 hard rules derived from physiology research. Claude generates the plan. The gate validates or rejects — not adjusts, not warns: *rejects.* |
| **Science** | Banister CTL/ATL/TSB · concurrent training interference (pickleball-primary) · pre-registered N-of-1 hypothesis catalog |
| **Stack** | Python 3.12 · FastAPI · DuckDB · Next.js 15 · React 19 · Tailwind v4 OKLCH · Claude Opus 4.7 |

---

## 🧪 agent-eval-kit

> *Your agent prompt drifted. You found out from a user, not from CI. That's what this is for.*

**[LLM regression-detection harness →](https://github.com/robsavage619/agent-eval-kit)** · MIT · Published on PyPI

```sh
uv add agent-eval-kit
```

Three judge types · exact match · numeric tolerance · LLM-as-judge (~$0.001/case) · regression diffing across prompt versions · per-run latency + cost tracking · JUnit XML for CI · Markdown for PR comments

---

## 🏟️ xfriars

> *San Diego in my bones. I wanted Padres analytics that treats the team seriously — a scan engine over real Statcast data, surfacing what the numbers actually show.*

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
![Claude API](https://img.shields.io/badge/Claude_API-CC785C?style=flat-square)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=astral&logoColor=white)

<div align="center">

<br/>

*"The discipline is in following the data, not the hunch."*

</div>
