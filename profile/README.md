<div align="center">

# FerroQuant

### Institutional-Grade Quantitative Trading. For Everyone.

[![Platform](https://img.shields.io/badge/Platform-ferroquant.com-00ff6a?style=for-the-badge&labelColor=0d1117)](https://ferroquant.com)
[![The Science](https://img.shields.io/badge/The_Science-Read_the_Whitepaper-58a6ff?style=for-the-badge&labelColor=0d1117)](https://ferroquant.github.io/research)

</div>

---

For decades, systematic quantitative trading has been the exclusive domain of hedge funds and institutional desks — requiring millions in infrastructure, proprietary data, and teams of quant researchers. **FerroQuant changes that.**

We built the same infrastructure from scratch. The same regime detection. The same strategy tournaments. The same ML signal filtering. Now it runs 24/7 across five asset classes — and you can access it.

---

## The System

| | |
|---|---|
| **Strategies** | 178 quantitative strategies running simultaneously |
| **Markets** | Crypto Futures · Crypto Spot · Forex · Stock Indices · Commodities |
| **Instruments** | 1,056+ symbols monitored in real-time |
| **Signal Engines** | 6 independent engines, each market isolated |
| **Historical Data** | 7 years validated across all markets |
| **Architecture** | Regime detection → Tournament selection → ML filtering → Live execution |

---

## How It Works

**Regime Detection** — Markets behave differently in trending vs ranging vs volatile conditions. Most strategies fail because they don't adapt. FerroQuant detects market state continuously and rotates strategies accordingly.

**Tournament-Based Selection** — 178 strategies compete on live market data. Only battle-tested strategies generate signals. The rest stay benched until conditions favour them.

**ML Signal Filtering** — Every signal passes through an ONNX ensemble model trained separately for LONG and SHORT positions. Noise is filtered before it reaches you.

**Multi-Asset Pipeline** — Crypto, forex, commodities, and stock indices run in a single unified pipeline. Cross-asset correlations inform signal confidence.

---

## Built With

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)

Signal engines and execution core in **Rust** for sub-millisecond latency. Data pipeline and infrastructure in **Go**. ML training and research in **Python**. Seven years of market data in **Parquet** on NVMe, queryable via **DuckDB** in milliseconds.

---

<div align="center">

**[→ Read the Science](https://ferroquant.github.io/research)** &nbsp;&nbsp;·&nbsp;&nbsp; **[→ Access the Platform](https://ferroquant.com)**

*The edge is systematic. The access is yours.*

</div>
