# Fahil Ejaz

**AI/ML Engineer · Data Scientist** — production RAG agents, LLM fine-tuning & serving, MLOps, and rigorous statistical evaluation.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fahil-ejaz/)
[![GitHub](https://img.shields.io/badge/GitHub-ejazfahil-181717?logo=github&logoColor=white)](https://github.com/ejazfahil)
![Focus](https://img.shields.io/badge/Focus-RAG_·_LLMOps_·_Data_Eng-6f42c1)

---

## About

I build production-grade AI systems that bridge research and deployment — stateful RAG agents, QLoRA fine-tuning pipelines, real-time drift monitoring, and statistically sound model evaluation. My work favors **honest benchmarks, maintainable code, and observable systems**.

- 🔭 **Currently:** production RAG & agents, QLoRA fine-tuning, MLOps & drift detection
- 🧪 **Specialties:** LLM/VLM evaluation, statistical inference, data engineering
- 🏭 **Domains:** Industrial AI, NLP, anomaly detection, reinforcement learning
- 🎯 **Open to:** AI Engineer · ML Engineer · Data Scientist · Research roles

> **On this portfolio:** every project README reports only what its code and committed artifacts can actually prove. Real outputs are cited as numbers; scaffolds and blueprints are labeled as such. No inflated metrics.

---

## ⭐ Featured Projects

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[Production RAG + Human-in-the-Loop Agent](https://github.com/ejazfahil/Production_RAG_HumanLoop_Agent)** | Stateful agent for industrial document intelligence — LangGraph state machine with a **human approval gate** (`retrieve → draft → grounding-check → approve → finalize/abstain`), pgvector retrieval, durable checkpointing, Prometheus metrics, and a Postgres audit trail. MIT-licensed, strictly typed. | `LangGraph` · `pgvector` · `FastAPI` · `Prometheus` |
| **[QLoRA → Quantize → Serve](https://github.com/ejazfahil/QLoRA-Fine-Tune-Quantization-served-with-vLLM)** | End-to-end 7B fine-tuning pipeline: **QLoRA (4-bit NF4) → eval → merge → AWQ → vLLM serving.** Config-driven, reproducible, transparent eval harness (GPU benchmarks marked pending — no placeholder numbers). | `PEFT` · `TRL` · `bitsandbytes` · `vLLM` |
| **[Vectorless RAG Lab](https://github.com/ejazfahil/ag_vectorless_RAG)** | Research harness comparing **7 embedding-free retrieval pipelines** — tree-navigation, BM25, agentic search, a hybrid RRF router, quote-extraction, and a novel three-stage hybrid. Local-first LLM client, telemetry, and a RAGAS / LLM-as-judge eval scaffold. | `BM25` · `RAGAS` · `Ollama` |
| **[AI for Business — 3 Case Studies](https://github.com/ejazfahil/AI_For_Business)** | Churn, energy forecasting & segmentation with **reproduced results**: churn ANN ≈ **84%** test accuracy, energy demand **Random Forest R² ≈ 0.68**, segmentation **silhouette ≈ 0.41 (k=2)**. | `TensorFlow` · `scikit-learn` · `pandas` |
| **[Bayesian LLM/VLM Evaluation](https://github.com/ejazfahil/bayesian-llm-eval)** | Goes beyond point estimates: **partial-pooling logistic model** (`correct ~ system + (1\|field) + (1\|doc_class)`) via Bambi/PyMC, posterior contrasts with 94% HDIs, ArviZ diagnostics & LOO. | `PyMC` · `Bambi` · `ArviZ` |
| **[Doc Extraction Benchmark (VLM vs OCR)](https://github.com/ejazfahil/doc-extraction-benchmark)** | Honest, pre-registered field-level extraction benchmark on **CORD** — Pixtral vs Tesseract/EasyOCR, normalized exact-match scoring, **document-clustered bootstrap CIs + exact McNemar** tests. | `Pixtral` · `Tesseract` · `pandera` · `SciPy` |

---

## 🏗️ Data & ML Engineering Suite

Focused, production-shaped building blocks — each a compact but working implementation.

| Repo | What it does | Stack |
| :--- | :--- | :--- |
| **[data-quality-framework](https://github.com/ejazfahil/data-quality-framework)** | Schema / null / range / freshness / SLA validators with HTML reports & alerts | `pandas` · `pytest` |
| **[airflow-etl-pipeline](https://github.com/ejazfahil/airflow-etl-pipeline)** | Production ETL DAGs: CSV→Postgres, API ingest, dbt trigger, Slack alerts | `Airflow` |
| **[dbt-analytics-models](https://github.com/ejazfahil/dbt-analytics-models)** | Staging → intermediate → mart models with schema tests & freshness SLAs | `dbt` · `SQL` |
| **[kafka-event-streaming](https://github.com/ejazfahil/kafka-event-streaming)** | Idempotent producers, manual-commit consumers, DLQ, replay, lag monitor | `Kafka` |
| **[spark-streaming-kafka](https://github.com/ejazfahil/spark-streaming-kafka)** | PySpark Structured Streaming: watermarked windowed aggregations + JDBC sink | `PySpark` |
| **[postgres-data-modeling](https://github.com/ejazfahil/postgres-data-modeling)** | Star schema, range partitioning, BRIN/partial indexing, Alembic, pgTAP | `PostgreSQL` |

---

## 🔬 Research & Applied ML

| Repo | Focus |
| :--- | :--- |
| **[mlops-drift-detector](https://github.com/ejazfahil/mlops-drift-detector)** | Real-time data/concept drift — PSI + Page-Hinkley, streaming monitor, Prometheus exporter |
| **[moon_lander_rl](https://github.com/ejazfahil/moon_lander_rl)** | Deep RL — DQN agent (PyTorch) on LunarLander-v3, with checkpoints, rollout videos & training curve |
| **[ALS_Disease_Severity](https://github.com/ejazfahil/ALS_Disease_Severity)** | Clinical ML — ALSFRS-R severity stratification from biomarker/functional features |
| **[OCR_Vision_Model_for_Industries](https://github.com/ejazfahil/OCR_Vision_Model_for_Industries)** | Modular industrial OCR framework — ensemble OCR + LLM verification, CER/WER metrics |
| **[genai-eval-framework](https://github.com/ejazfahil/genai-eval-framework)** | LLM eval harness — parallel MMLU evaluator, Anthropic/Ollama adapters, on-disk caching |

---

## 🛠️ Tech Stack

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

**LLM & GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FF9A00?logo=huggingface&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![PEFT / QLoRA](https://img.shields.io/badge/PEFT_·_QLoRA-5A29E4)
![vLLM](https://img.shields.io/badge/vLLM-7B3FE4)
![PyMC](https://img.shields.io/badge/PyMC_·_Bayesian-EB5E28)

**Data & MLOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)

---

<sub>Building production AI systems that work in the real world · Open to AI/ML Engineering, Data Science & Research opportunities · [linkedin.com/in/fahil-ejaz](https://www.linkedin.com/in/fahil-ejaz/)</sub>
