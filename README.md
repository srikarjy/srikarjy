<div align="center">

# Hi, I'm Srikar 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Backend+%26+ML+Engineer;Building+RAG+%2B+Multi-Agent+Systems;Biotech+Background+%E2%86%92+Production+ML;Data+Scientist+Fellow+%40+ChiEAC" alt="Typing SVG" />

MS Computer Science, Boston University (Jan 2026) 

Backend + ML engineer specializing in **LLM/agent systems, RAG, and MLOps** — I build retrieval pipelines, multi-agent architectures, and production infrastructure, and I benchmark every one of them against a real baseline before calling it done.

[![Email](https://img.shields.io/badge/Email-srikarjy77%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:srikarjy77@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-srikarjy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srikarjy)

</div>

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[🔁 Durable Workflow Engine](https://github.com/srikarjy/workflow-Engine)** · Exactly-once workflow engine in Go, sagas defined in YAML

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

Go engine giving distributed workflows exactly-once execution — idempotent steps, Postgres-backed crash recovery, real saga rollbacks.
**35/35** fault-injection tests passed (SIGKILL + concurrent races) — **0 double executions, 0 lost steps**.

</td>
<td width="50%" valign="top">

**[🧬 FlowCast](https://github.com/srikarjy/Flowcast)** · Anomaly detection + LLM root-cause analysis for RNA-seq pipelines

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

Go CLI that flags anomalous RNA-seq runs with a statistical classifier, then has an LLM narrate the likely root cause.
**F1 0.870** (23% lift over baseline); grounding the LLM cut unsupported claims **39.6% → 9.4%**.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[⚖️ Aletheia](https://github.com/srikarjy/Aletheia)** · Multi-agent debate system for scientific claim verification

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)

LangGraph pipeline where agents argue opposing positions and cross-examine each other before reaching a verdict.
Confidence calibration (ECE) improved **0.184 → 0.117**; caught **13/16** known hallucination regressions.

</td>
<td width="50%" valign="top">

**[🩸 GlucoPulse](https://github.com/srikarjy/GlucoPulse)** · Real-time forecasting pipeline, ingestion to serving

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

End-to-end streaming stack — Kafka ingestion, TimescaleDB, PySpark features, a Transformer model served via ONNX, Airflow-orchestrated.
Forecasts blood sugar 30-60 min ahead, benchmarked against a persistence baseline in production-shaped infra.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[📱 BioFeed AI](https://github.com/srikarjy/BioFeed-AI)** · Recommendation engine + anomaly detection, iOS + FastAPI

![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

SwiftUI app backed by a FastAPI service, using implicit-feedback recommendations plus anomaly detection on company activity.
**30% CTR lift** over a popularity baseline across 8,500+ articles.

</td>
<td width="50%" valign="top">

**[🔐 Biolab MCP Server](https://github.com/srikarjy/biolab-mcp-server)** · Provenance & auth layer for AI agents querying bio databases

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

MCP server that logs every AI agent query against bio databases with full retrieval context and a traceable `retrieval_id`.
Multi-tenant JWT auth + SSE streaming — every AI-generated answer is auditable back to its source.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🧫 metalsw](https://github.com/srikarjy/metalsw)** · GPU-accelerated exact sequence alignment (Metal, Apple Silicon)

![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Metal](https://img.shields.io/badge/Metal-000000?style=flat-square&logo=apple&logoColor=white)

Metal compute-shader implementation of exact Smith-Waterman protein search, verified bit-for-bit against a CPU oracle.
**13.5x** the throughput of Parasail's SIMD CPU implementation, **0 mismatches** across 78,006 comparisons.

</td>
<td width="50%" valign="top">

**[🔬 Research-Orchestrator](https://github.com/srikarjy/Research-Orchestrator)** · Capstone: agentic research assistant with human-in-the-loop review

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

Capstone unifying Aletheia (debate), Workflow Engine (exactly-once execution), and Biolab MCP Server (auditable evidence) behind human review.
Built to align with 21 CFR Part 11 / ALCOA+ — the FDA's data-integrity standards.

</td>
</tr>
</table>

---

### 🛠️ Tech Stack

**Languages**
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Backend & Infra**
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

**AI / ML / Agents**
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/-RAG-8A2BE2?style=flat-square)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![QLoRA](https://img.shields.io/badge/-QLoRA%2FPEFT-FF6F00?style=flat-square)
![FAISS](https://img.shields.io/badge/-FAISS-4285F4?style=flat-square)
![pgvector](https://img.shields.io/badge/-pgvector-336791?style=flat-square)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

**Data Engineering**
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PySpark](https://img.shields.io/badge/-PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/-TimescaleDB-FDB515?style=flat-square&logo=postgresql&logoColor=black)
![Neo4j](https://img.shields.io/badge/-Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

**GPU / Computational Biology**
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Metal](https://img.shields.io/badge/-Metal-000000?style=flat-square&logo=apple&logoColor=white)
![PubMed](https://img.shields.io/badge/-PubMed-326599?style=flat-square)
![ChEMBL](https://img.shields.io/badge/-ChEMBL-7C3AED?style=flat-square)
![UniProt](https://img.shields.io/badge/-UniProt-1BA3E0?style=flat-square)

**Cloud & Observability**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![SageMaker](https://img.shields.io/badge/-SageMaker-01A88D?style=flat-square)
![Bedrock](https://img.shields.io/badge/-Bedrock-8C4FFF?style=flat-square)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=srikarjy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=srikarjy&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=srikarjy&theme=tokyonight&hide_border=true" />
</div>

---

<div align="center">

📫 **Open to backend, ML engineering, and computational biology roles** where rigor matters more than hype.

</div>
