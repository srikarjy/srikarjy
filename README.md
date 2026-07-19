## Hi, I'm Srikar 👋

**Backend & ML Engineer** | Data Scientist Fellow @ ChiEAC | MS Computer Science, Boston University (Jan 2026) | Biotech background

I build retrieval systems, agentic pipelines, and provenance infrastructure for biomedical and scientific applications, then validate them against real baselines instead of shipping something that just sounds impressive.

### 🚀 Featured Projects

**[FlowCast](https://github.com/srikarjy/Flowcast)** — Go CLI that diagnoses nf-core/rnaseq pipeline runs. A modified Z-score (MAD) classifier hit F1 0.870 against a 56-sample labeled set, a 23% improvement over a fixed-threshold baseline. The LLM narration layer cut unsupported causal claims from 39.6% to 9.4% against an unconstrained LLM baseline on a 48-case golden set.

**[Aletheia](https://github.com/srikarjy/Aletheia)** — Multi-agent scientific reasoning system where agents with distinct epistemic roles debate a claim before producing a conclusion, with every piece of evidence traced to its exact source and retrieval step. Historical-outcome calibration reduced confidence ECE from 0.184 to 0.117, and counterfactual evaluation caught 13 of 16 known memory-induced regressions.

**[GlucoPulse](https://github.com/srikarjy/GlucoPulse)** — Real-time streaming pipeline for continuous glucose monitor data. Full stack from ingestion to serving: Kafka, TimescaleDB, PySpark, Airflow, PyTorch, ONNX, FastAPI, Grafana. TFT model evaluated against a persistence baseline at 30 and 60 minute forecast horizons.

**[BioFeed AI](https://github.com/srikarjy/BioFeed-AI)** — iOS biotech intelligence app (SwiftUI + FastAPI) with an implicit-feedback recommendation engine improving offline replay CTR 30% over a popularity baseline across 8,500+ articles, plus an anomaly detection pipeline correlating article-volume spikes with stock movement, surfacing 3 candidate early-signal events in a 2-month backtest.

**[Biolab MCP Server](https://github.com/srikarjy/biolab-mcp-server)** — Python MCP server that sits between AI agents and biological databases, logging every query with full retrieval context and returning a `retrieval_id` for end-to-end provenance, multi-tenant with JWT and SSE support.

**[PharmGraph](https://github.com/srikarjy/PharmGraph)** — Interactive pharmacogenomic interaction network explorer sourced live from Open Targets, deduplicated and ranked by CPIC evidence level.

### 🛠️ Tech Stack

**Backend:** Python | FastAPI | PostgreSQL | Redis | Docker | Go
**ML/AI:** PyTorch | PubMedBERT/BioBERT | Sentence Transformers | FAISS | pgvector
**LLMs & Agents:** LangGraph | RAG | Multi-agent orchestration | QLoRA (PEFT) | MCP
**Data Infra:** Kafka | TimescaleDB | PySpark | Airflow | Neo4j
**Cloud:** AWS (Lambda, S3, SageMaker, Bedrock) | pursuing AWS CCP and SAA-C03

### 📫 Connect

- 📧 Email: srikarjy025@gmail.com
- 💼 LinkedIn: [linkedin.com/in/srikaryadhunandan-142309162](https://www.linkedin.com/in/srikaryadhunandan-142309162)
