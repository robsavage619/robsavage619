## Rob Savage

I build rigorous decision-support systems — for baseball front offices, financial research, and personal performance. Sports analytics, agentic AI, and the discipline to know when the data is actually telling you something.

Day job: cloud cost engineering and LLM agent infrastructure at Nike. Portland, OR.

Looking for roles in sports analytics, AI systems, and platform engineering.

[LinkedIn](https://www.linkedin.com/in/robsavage/) · rob.savage@me.com

---

**[savage-trade-evaluator](https://github.com/robsavage619/savage-trade-evaluator)** — MLB front-office trade evaluation platform. 1.29M+ rows of transaction, performance, contract, and front-office personnel data in a single DuckDB store. A War Room that reads a club's record, payroll, CBT headroom, and roster shape and tells the GM what to do about it. Context-aware valuation: the same player is worth different things to different clubs. Bayesian modeling throughout (PyMC, CRPS, posterior distributions). 35 research rounds — the original thesis was empirically rejected, and the platform reports that. AI Intelligence Brief via structured-output agent grounded in live data. RAG over the research corpus. Source-available.

**[cortex](https://github.com/robsavage619/cortex)** — Quantitative research platform: point-in-time factor engine over the S&P 500, alt-data ingestion from SEC EDGAR and Senate congressional trades, pre-registered backtest harness with Newey-West HAC-corrected t-stats, Brier score calibration on every investment thesis. FastAPI + DuckDB + React. Source-available.

**[savage-labs](https://github.com/robsavage619/savage-labs)** — Personal performance platform: WHOOP + Apple Health + Hevy + DUPR integrated through a single typed DailyState. Drug-adjusted HRV, Gabbett ACWR from fused wearable strain and lifting tonnage, 20-rule deterministic gate engine that validates Claude's workout plans before they're shown, pre-registered N-of-1 hypothesis catalog with auto-rotation. Banister CTL/ATL/TSB. Next.js + FastAPI + DuckDB.

**[agent-eval-kit](https://github.com/robsavage619/agent-eval-kit)** — Regression-detection harness for LangGraph + Claude agents. Golden-set evals, three judge types (exact match, numeric tolerance, LLM-as-judge), regression diffing across prompt versions, JUnit XML for CI. `uv add agent-eval-kit`

---

`Python 3.12` · `LangGraph` · `Claude API` · `Databricks` · `FastAPI` · `DuckDB` · `React` · `PyMC` · `uv` · `ruff` · `pyright`
