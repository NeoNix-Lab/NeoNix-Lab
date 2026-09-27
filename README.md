<p align="center">
  <img src="assets/neonic-avatar.png" width="180" alt="NeoNix-Lab avatar" /><br>
  <em>"I build on what others have built — so that the next can build higher."</em>
</p>

---

## 🏛️ Flagship Project: [Quant Platform](https://github.com/NeoNix-Lab/quant-platform)

[![Quant Platform integrity](https://github.com/NeoNix-Lab/quant-platform/actions/workflows/integrity.yml/badge.svg)](https://github.com/NeoNix-Lab/quant-platform/actions/workflows/integrity.yml)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PostgreSQL 17](https://img.shields.io/badge/postgresql-17-336791.svg)](https://www.postgresql.org/)
[![License: Proprietary](https://img.shields.io/badge/license-Source--Available-red.svg)](https://github.com/NeoNix-Lab/quant-platform/blob/main/LICENSE)

**Quant Platform** is my primary engineering endeavor: a modular quantitative research, market-data, and deterministic trading infrastructure designed around reproducibility, explicit semantic contracts, and strict architectural boundaries.

Developed as a modular monolith with strict separation between layers:
- **Canonical Data Plane**: L2 Bybit trade ingest, `trade-v1`, Parquet storage roots, and PostgreSQL catalog DDL.
- **DataGateway Boundary**: Causal historical and live data streaming (`scan()` and `read()`).
- **Representations & Features**: Point-in-time candles, footprints, and feature computation with availability floors.
- **Validation Engine**: Purged & embargoed walk-forward cross-validation splits, preventing predictive leakage.
- **Strategy & Policy Composition**: Learner-agnostic `DecisionIntent`, multi-signal combinations, capital risk budgets, session calendars, and streak cooldowns.
- **Unified Execution Engine**: Order state machine, fee schedules, synthetic slippage models, intra-bar execution conflict and OCO resolvers.
- **Portfolio Accounting**: Double-entry journal, multi-asset hedge-mode positions, cash & asset conservation, and mark-to-market equity curves.
- **Deterministic Historical Replay Runtime**: Bitwise-reproducible historical simulations with immutable trace fingerprints.

🔹 **Core Stack**: Python 3.11+ · PostgreSQL 17 · Apache Parquet · Linux · GitHub Actions  
👉 **[Explore Quant Platform on GitHub ➔](https://github.com/NeoNix-Lab/quant-platform)**

```text
Market Data
     ↓
Canonical Data Plane (Parquet / Natural Partitioning)
     ↓
DataGateway Boundary (scan & read)
     ↓
Representations & Features (Candles, Footprints, Features)
     ↓
Research & Validation (Causal Floor, Purged & Embargoed Folds)
     ↓
Strategy & Policy Gates (Signals, Sizing, Risk Budgets, Cooldowns)
     ↓
Unified Execution Engine (Orders, Fills, Slippage, Fees, OCO Resolvers)
     ↓
Double-Entry Portfolio Ledger & Deterministic Replay (Trace Fingerprints)
```

---

## 👋 About Me

I'm **Nicola Montanari** — a self-taught developer focused on quantitative systems, software architecture, automation, and applied machine learning.

My main technical interests:
- **Quantitative research infrastructure** & deterministic simulation engines
- **Algorithmic execution systems** & double-entry portfolio accounting
- **Deterministic computation** & bitwise reproducibility
- **Market-data pipelines** & high-throughput streaming
- **Modular software architecture** & ADR-driven engineering
- **AI-assisted software engineering** & autonomous developer workflows

---

## 🛠️ Engineering Approach

I build systems around non-negotiable principles:

> **Contracts before coupling · Evidence before assumptions · Deterministic behavior · Explicit ownership · Reproducibility by design**

---

## 📦 Other Projects & Background

Previous work and modular tools developed around trading platforms and reinforcement learning experiments:

| Project | Tech Stack | Description |
| :--- | :---: | :--- |
| [`Neo.Quantower.Toolkit`](https://github.com/Nico88-Vs/NeoQuantowerTools.git) | C# / .NET | Modular tooling and plugin framework extending the Quantower platform |
| [`Neo.Quantower.StrategyAnalysisPlatform`](https://github.com/NeoNix-Lab/StrategyAnalysisPlatform.git) | React / TypeScript | Web-based trading analytics platform to evaluate and compare strategies |
| [`Strategy Manager`](https://github.com/Nico88-Vs/Quantower-Orders-Manager.git) | C# | Quantower strategy, position, SL/TP and performance metrics management |
| [`RL.Training.Core`](https://github.com/Nico88-Vs/Rnn_V0_1.git) | Python / TensorFlow | Infrastructure for reinforcement learning experiments with Streamlit UI |
| [`RL.Quantower.UIBridge`](https://github.com/Nico88-Vs/QT_Ai_Plug_In_Integration.git) | C# / Python | Experimental Quantower integration bridging RL agents to live charts |

---

## 📫 Contact

- 📧 Email: [nicoladotmontanari@yahoo.com](mailto:nicoladotmontanari@yahoo.com)
- 🐙 GitHub: [@NeoNix-Lab](https://github.com/NeoNix-Lab)
