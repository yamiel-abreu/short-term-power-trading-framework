# Short-Term Power Trading Framework (Renewables & Flexibility)

A systems-level quantitative engineering portfolio focused on short-term European power markets.
This repository demonstrates an end-to-end pipeline from raw market signals to production-grade
forecasting and optimization components, with emphasis on robustness, reproducibility, and
business-value metrics (PnL proxies, opportunity capture, risk-aware performance).

## Scope (Roadmap)
- **Project 1 — Day-Ahead Price Forecasting Engine**: data pipeline, feature engineering, walk-forward validation, monitoring-ready outputs.
- **Project 2 — BESS Optimization (Multi-market)**: constraint-aware dispatch optimization and revenue decomposition.
- **Project 3 — Intraday Strategy Framework**: modular strategy interface, backtesting, slippage, risk, performance tracking.
- **Project 4 — Renewables Forecast Error Strategy**: signal research around intermittency and imbalance risk.

## Engineering Principles
- Reproducible runs via config files
- Modular architecture (data → features → model → validation → reporting)
- Testable core components
- Monitoring-oriented outputs to support dashboards

## Tech Stack
Python, pandas, numpy, scikit-learn, SQL-ready pipelines, Plotly (dashboarding)

## Disclaimer
This is a research/portfolio project. It does not constitute financial or trading advice.
