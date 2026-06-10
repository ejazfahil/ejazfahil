<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Fahil%20Ejaz&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=AI%2FML%20Engineer%20·%20Data%20Scientist%20·%20RAG%20·%20LLM%20Fine-Tuning%20·%20MLOps&descAlignY=55&descSize=16" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fahil-ejaz/)
[![GitHub followers](https://img.shields.io/github/followers/ejazfahil?style=for-the-badge&logo=github)](https://github.com/ejazfahil)

</div>

---

## 👋 About Me

I'm an **AI/ML Engineer & Data Scientist** who builds production-grade AI systems — stateful RAG agents, LLM fine-tuning & serving pipelines, real-time MLOps infrastructure, and rigorous statistical evaluation. My focus is bridging research and production: **honest benchmarks, maintainable code, and observable systems.**

```python
engineer = {
    "current_focus":  ["Production RAG & Agents", "QLoRA Fine-Tuning", "MLOps & Drift Detection"],
    "specialties":    ["LLM/VLM Evaluation", "Statistical Inference", "Data Engineering"],
    "domains":        ["Industrial AI", "NLP", "Anomaly Detection", "Reinforcement Learning"],
    "principle":      "Report only what the code can prove.",
    "open_to":        "AI Engineer · ML Engineer · Data Scientist · Research roles",
}
```

> 🧭 **A note on this portfolio:** every README is scoped strictly to what the code and committed artifacts actually demonstrate. Where a project reports numbers, they come from real outputs; where work is still a scaffold or blueprint, it says so. No inflated metrics.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 🤖 [Production RAG + Human-in-the-Loop Agent](https://github.com/ejazfahil/Production_RAG_HumanLoop_Agent)
Stateful RAG agent for industrial document intelligence. **LangGraph** state machine (`retrieve → draft → grounding-check → HITL approval gate → finalize/abstain`), pgvector retrieval, durable checkpointing, Prometheus metrics, and a Postgres JSONB audit trail. MIT-licensed, strictly typed.

`LangGraph` `pgvector` `FastAPI` `Prometheus` `Docker`

</td>
<td width="50%">

### 🦙 [QLoRA → Quantize → Serve](https://github.com/ejazfahil/QLoRA-Fine-Tune-Quantization-served-with-vLLM)
End-to-end 7B fine-tuning pipeline: **QLoRA (4-bit NF4)** → eval → merge → **AWQ** → **vLLM** serving. Config-driven and reproducible, with a transparent eval harness (GPU benchmarks marked pending — no placeholder numbers).

`PEFT` `TRL` `bitsandbytes` `AWQ` `vLLM`

</td>
</tr>
<tr>
<td width="50%">

### 🔍 [Vectorless RAG Lab](https://github.com/ejazfahil/ag_vectorless_RAG)
A research harness comparing **7 embedding-free retrieval pipelines** — PageIndex tree-navigation, BM25, agentic search, a hybrid RRF router, an embedding-free quote-extraction method, and a novel three-stage hybrid. Local-first LLM client, telemetry tracking, and a RAGAS / LLM-as-judge eval scaffold.

`BM25` `RAGAS` `Ollama` `LLM-as-Judge`

</td>
<td width="50%">

### 📈 [AI for Business — 3 Case Studies](https://github.com/ejazfahil/AI_For_Business)
Churn, energy forecasting & customer segmentation with **real, reproduced results**: churn ANN ≈ **84% test accuracy**, energy demand **Random Forest R² ≈ 0.68**, and customer segmentation **silhouette ≈ 0.41 (k=2)** with PCA visualization.

`TensorFlow/Keras` `scikit-learn` `pandas` `Jupyter`

</td>
</tr>
<tr>
<td width="50%">

### 📐 [Bayesian LLM/VLM Evaluation](https://github.com/ejazfahil/bayesian-llm-eval)
Hierarchical Bayesian evaluation that goes beyond point estimates: **partial-pooling logistic model** (`correct ~ system + (1|field) + (1|doc_class)`) via **Bambi/PyMC**, posterior contrasts with 94% HDIs, plus ArviZ diagnostics & LOO.

`PyMC` `Bambi` `ArviZ` `Typer`

</td>
<td width="50%">

### 🧾 [Doc Extraction Benchmark (VLM vs OCR)](https://github.com/ejazfahil/doc-extraction-benchmark)
An honest, pre-registered field-level extraction benchmark on **CORD** — VLM (Pixtral) vs Tesseract/EasyOCR, with normalized exact-match scoring and **document-clustered bootstrap CIs + exact McNemar** tests for statistically sound comparisons.

`Mistral/Pixtral` `Tesseract` `pandera` `SciPy`

</td>
</tr>
</table>

<div align="center">
<sub><b>More:</b>
<a href="https://github.com/ejazfahil/mlops-drift-detector">MLOps Drift Detector</a> (PSI + Page-Hinkley, Prometheus) ·
<a href="https://github.com/ejazfahil/moon_lander_rl">Moon Lander RL</a> (DQN, PyTorch) ·
<a href="https://github.com/ejazfahil/ALS_Disease_Severity">ALS Severity Modeling</a> ·
<a href="https://github.com/ejazfahil/OCR_Vision_Model_for_Industries">Industrial OCR Framework</a>
</sub>
</div>

---

## 🏗️ Data & ML Engineering Suite

A set of focused, production-shaped building blocks — each a compact but working implementation:

| Repo | What it does | Stack |
|------|--------------|-------|
| [data-quality-framework](https://github.com/ejazfahil/data-quality-framework) | Schema / null / range / freshness / SLA validators + HTML reports & alerts | `pandas` `pytest` |
| [airflow-etl-pipeline](https://github.com/ejazfahil/airflow-etl-pipeline) | Production ETL DAGs: CSV→Postgres, API ingest, dbt trigger, Slack alerts | `Airflow` |
| [dbt-analytics-models](https://github.com/ejazfahil/dbt-analytics-models) | Staging → intermediate → mart models with schema tests & freshness SLAs | `dbt` `SQL` |
| [kafka-event-streaming](https://github.com/ejazfahil/kafka-event-streaming) | Idempotent producers, manual-commit consumers, DLQ, replay, lag monitor | `Kafka` |
| [spark-streaming-kafka](https://github.com/ejazfahil/spark-streaming-kafka) | PySpark Structured Streaming: watermarked windowed aggregations + JDBC sink | `PySpark` |
| [postgres-data-modeling](https://github.com/ejazfahil/postgres-data-modeling) | Star schema, range partitioning, BRIN/partial indexing, Alembic, pgTAP | `PostgreSQL` |

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**LLM & ML**

![HuggingFace](https://img.shields.io/badge/HuggingFace-FF9A00?style=flat-square&logo=huggingface&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![PEFT](https://img.shields.io/badge/PEFT%2FQLoRA-blue?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-purple?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyMC](https://img.shields.io/badge/PyMC-Bayesian-eb5e28?style=flat-square)

**Data & MLOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
<img height="160" src="https://github-readme-stats.vercel.app/api?username=ejazfahil&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ejazfahil&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>
</div>

---

<div align="center">
<sub>Building production AI systems that work in the real world · Open to AI/ML Engineering, Data Science & Research opportunities</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
