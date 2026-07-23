<div align="center">
<img src="assets/hero.svg" alt="Srikar Yadhunandan banner" width="100%" />
</div>


<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Srikar_Yadhunandan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/srikar-yadhunandan-142309162)
[![Location](https://img.shields.io/badge/Chicago,_IL-ChiEAC-10B981?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

</div>

## About

I am a Data Scientist Fellow (AI/ML & Backend Engineering) at ChiEAC in Chicago, working across ML pipelines, iOS development, and backend platform engineering. My background bridges biotechnology and computer science: a B.Tech in Biotechnology from Manipal Institute of Technology, followed by an MS in Computer Science from Boston University.

I build the kind of systems that sit at the boundary of biology and machine learning: RAG pipelines over scientific literature, agentic reasoning systems that refuse unsupported claims, forecasting models on clinical time series, and the backend infrastructure to ship all of it. My work is published in IEEE FNWF 2024 (`arXiv:2504.18029`).

**Currently building:** BioFeed AI, a native iOS biotech intelligence app I am building end to end, SwiftUI front end, FastAPI/Python backend, semantic search across an 8,500+ article corpus, and a personalized recommendation engine.

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧬 [FlowCast](https://github.com/srikarjy/FlowCast)
A Go CLI that parses Nextflow trace and MultiQC output from nf-core/rnaseq runs and narrates QC failures with honest, confidence-tagged reasoning instead of guessing at causes.

- Modified Z-score (MAD) classifier: **F1 0.870** vs. 0.706 fixed-threshold baseline (+23.2%)
- Claude API narrator tags every claim Observed / Reported / Unknown, cutting unsupported causal claims **76.3%** on a 48-case golden set
- Deterministic replay via a Go + Python event log backed by SQLite

`Go` `Python` `SQLite` `OpenTelemetry`

</td>
<td width="50%" valign="top">

### 🩸 [GlucoPulse](https://github.com/srikarjy/GlucoPulse)
A glucose forecasting pipeline built on 306K+ real CPGM readings from 25 Type 1 diabetes patients, from raw ingestion through a Temporal Fusion Transformer served in production.

- 30 min horizon: **RMSE ‑25.0%**, Zone A **+8.8pp** (91.2%) vs. persistence baseline
- 60 min horizon: **RMSE ‑21.0%**, Zone A **+10.4pp** (78.6%)
- Kafka ingestion, TimescaleDB hypertables, PySpark feature engineering, Airflow, ONNX/INT8 inference

`Kafka` `PyTorch` `TimescaleDB` `Airflow` `ONNX`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [Aletheia](https://github.com/srikarjy/Aletheia)
A multi-agent debate system (advocate, skeptic, empiricist, synthesizer) that calibrates its own confidence against memory of past debates, and knows when it doesn't have enough evidence to trust that memory.

- Expected Calibration Error reduced **0.184 → 0.117** using 47 prior debate results
- Detects **13/16** known memory-induced regressions via automated counterfactual evaluation
- LangGraph StateGraph orchestration with thread-scoped and cross-thread memory stores

`Python` `LangGraph` `PostgreSQL` `Claude API`

</td>
<td width="50%" valign="top">

### 🔬 [PharmGraph](https://github.com/srikarjy/PharmGraph)
A full-stack pharmacogenomics graph explorer that reconciles messy, duplicated clinical annotation data into a clean, provenance-tracked knowledge graph.

- Disambiguated **28** protein IDs, collapsed **343** duplicate CYP2C9 rows
- Two-layer provenance cross-referencing PharmGKB and PubMed
- CPIC evidence tiering with **31** passing tests

`Python` `Neo4j` `React`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ [Biolab MCP Server](https://github.com/srikarjy/biolab-mcp-server)
A production-grade, multi-tenant MCP server exposing biolab data sources (ClinVar, ChEMBL, PubMed) over a proper backend, JWT auth, SSE streaming, and rate limiting included.

`Go` `JWT` `SSE`

</td>
<td width="50%" valign="top">

### 📱 BioFeed AI *(in progress)*
A native SwiftUI iOS app that aggregates biotech literature and news across 200+ tickers, deduplicates semantically over an 8,500+ article corpus, and learns what to surface from real click and dwell-time signals.

- Recommendation system improves offline replay CTR **+30%** over a popularity baseline
- Anomaly detection pipeline surfaced 3 candidate early-signal events in a 2-month historical backtest

`SwiftUI` `FastAPI` `PostgreSQL` `Docker`

</td>
</tr>
</table>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=srikarjy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Srikar's GitHub stats" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=srikarjy&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" width="30%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=srikarjy&theme=tokyonight&hide_border=true" alt="GitHub streak" width="60%" />

</div>

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/srikar-yadhunandan-142309162)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/srikarjy)

</div>
