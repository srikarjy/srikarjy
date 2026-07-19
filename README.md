<div align="center">

# Hi, I'm Srikar 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Backend+%26+ML+Engineer;Building+RAG+%2B+Multi-Agent+Systems;Biotech+Background+%E2%86%92+Production+ML;Data+Scientist+Fellow+%40+ChiEAC" alt="Typing SVG" />

**Data Scientist Fellow @ ChiEAC** · MS Computer Science, Boston University (Jan 2026) · Biotech background

I build retrieval systems, agentic pipelines, and provenance infrastructure for biomedical and scientific applications, validated against real baselines, not vibes.

[![Email](https://img.shields.io/badge/Email-srikarjy025%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:srikarjy025@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-srikaryadhunandan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srikaryadhunandan-142309162)

</div>

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[🧬 FlowCast](https://github.com/srikarjy/Flowcast)**
Go CLI diagnosing nf-core/rnaseq pipeline runs

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

Modified Z-score (MAD) classifier → **F1 0.870**, a **23% lift** over fixed-threshold baseline. LLM narration cut unsupported causal claims **39.6% → 9.4%** on a 48-case golden set.

</td>
<td width="50%" valign="top">

**[⚖️ Aletheia](https://github.com/srikarjy/Aletheia)**
Multi-agent scientific reasoning, agents debate before concluding

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)

Historical-outcome calibration cut confidence ECE **0.184 → 0.117**. Counterfactual eval caught **13/16** known memory-induced regressions.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🩸 GlucoPulse](https://github.com/srikarjy/GlucoPulse)**
Real-time CGM streaming pipeline, ingestion to serving

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

TFT model evaluated against a persistence baseline at 30 and 60 minute forecast horizons. Full stack: Kafka, TimescaleDB, PySpark, Airflow, ONNX, Grafana.

</td>
<td width="50%" valign="top">

**[📱 BioFeed AI](https://github.com/srikarjy/BioFeed-AI)**
iOS biotech intelligence app, SwiftUI + FastAPI

![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

Implicit-feedback recs improve CTR **30%** over popularity baseline across 8,500+ articles. Anomaly detection surfaced **3 candidate signals** in a 2-month backtest.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🔐 Biolab MCP Server](https://github.com/srikarjy/biolab-mcp-server)**
Provenance layer between AI agents and bio databases

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

Every query logged with full retrieval context, returns a `retrieval_id` for end-to-end lineage. Multi-tenant, JWT auth, SSE streaming.

</td>
<td width="50%" valign="top">

**[💊 PharmGraph](https://github.com/srikarjy/PharmGraph)**
Pharmacogenomic interaction network explorer

![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

Live-sourced from Open Targets, deduplicated and ranked by CPIC evidence level for genes, proteins, and drugs.

</td>
</tr>
</table>

---

### 🕸️ Knowledge Graph — Skills → Problems → Projects

```mermaid
graph LR
    A[Srikar] --> B[Backend Engineering]
    A --> C[ML and Retrieval]
    A --> D[LLM and Agent Systems]
    A --> E[Data Infrastructure]
    A --> F[Cloud]

    B --> B1[FastAPI]
    B --> B2[PostgreSQL]
    B --> B3[Go]
    B --> BP1["Problem: async API p95 latency 8s"]
    B --> BP2["Problem: serving retrieval at scale"]
    BP1 -.-> P1[["Gutslane ERP<br/>8s to 200ms"]]
    BP2 -.-> P2[["ChiEAC Platform<br/>190 req/s, 4-5ms"]]

    C --> C1[PyTorch]
    C --> C2[PubMedBERT / BioBERT]
    C --> C3[FAISS / pgvector]
    C --> CP1["Problem: semantic search over biomedical corpus"]
    C --> CP2["Problem: pharmacogenomic data is duplicated and unranked"]
    CP1 -.-> P2
    CP2 -.-> P3[["PharmGraph<br/>CPIC-ranked network"]]

    D --> D1[LangGraph]
    D --> D2[RAG]
    D --> D3[QLoRA / PEFT]
    D --> D4[MCP]
    D --> DP1["Problem: LLM narration invents unsupported claims"]
    D --> DP2["Problem: multi-agent confidence isn't calibrated"]
    D --> DP3["Problem: agent queries to bio DBs leave no audit trail"]
    DP1 -.-> P4[["FlowCast<br/>39.6% to 9.4% unsupported claims"]]
    DP2 -.-> P5[["Aletheia<br/>ECE 0.184 to 0.117"]]
    DP3 -.-> P6[["Biolab MCP Server<br/>retrieval_id lineage"]]

    E --> E1[Kafka]
    E --> E2[Airflow / PySpark]
    E --> E3[Neo4j]
    E --> EP1["Problem: silent sensor data loss in real time streams"]
    E --> EP2["Problem: tracking my own dev activity across tools"]
    EP1 -.-> P7[["GlucoPulse<br/>Kafka to TimescaleDB to PyTorch"]]
    EP2 -.-> P8[["Personal KG<br/>Neo4j + pgvector hybrid RAG"]]

    F --> F1[AWS SageMaker / Bedrock]
    F --> F2[Lambda]
    F --> FP1["Currently: AWS CCP, then SAA-C03"]
```

*Every branch traces back to a shipped project with a measured result, not a tutorial repo. The `Personal KG` node is a live instance of the hybrid RAG architecture I use in Aletheia and Biolab, applied to my own Claude Code and research activity.*

---

### 🛠️ Tech Stack

**Backend**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**ML / AI**
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS-4285F4?style=flat-square)
![pgvector](https://img.shields.io/badge/-pgvector-336791?style=flat-square)

**LLMs & Agents**
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/-RAG-8A2BE2?style=flat-square)
![QLoRA](https://img.shields.io/badge/-QLoRA%2FPEFT-FF6F00?style=flat-square)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square)

**Data Infra**
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/-PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Neo4j](https://img.shields.io/badge/-Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

**Cloud**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![SageMaker](https://img.shields.io/badge/-SageMaker-01A88D?style=flat-square)
![Bedrock](https://img.shields.io/badge/-Bedrock-8C4FFF?style=flat-square)

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
