<h1 align="center">Jaivinay Gudiveka</h1>

<p align="center">
  Data & AI engineer. I build things that run, not just notebooks that ran once.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jaivinay-gudiveka"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://jaivinay.github.io"><img src="https://img.shields.io/badge/Portfolio-181717?style=flat&logo=github&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:jaivinaygudiveka@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

MS in Artificial Intelligence & Business Analytics, University of South Florida (Aug 2024 – Dec 2025). Based in Tampa, FL.

I spend most of my time on two things: moving data reliably at scale, and getting language models to do useful work on top of it. The projects below are the ones I'd want to talk through in an interview — streaming pipelines, forecasting models, and retrieval systems, each with the design decisions written down.

**Open to Data Analyst, Data Scientist, and AI/ML Engineer roles — available immediately.**

---

## Featured work

### [Multi-PDF RAG Assistant](https://github.com/Jaivinay/multi-pdf-rag-assistant)
Upload a stack of PDFs, ask questions in plain English, get answers with page-level citations. Runs entirely on your own machine — no API keys, no data leaving the box.
*The interesting part:* tuning chunk size and overlap against retrieval quality, and keeping FAISS indexes persistent so the knowledge base survives a restart.
`LangChain` `FAISS` `Ollama` `Llama 3.2` `Streamlit`

### [Real-Time Weather Data Pipeline](https://github.com/Jaivinay/Real-Time-Weather-Data-Pipeline)
End-to-end streaming pipeline: API ingest through Kafka, processed in Spark, staged in MinIO, orchestrated by Airflow, landed in Snowflake.
*The interesting part:* the orchestration, not the transforms — retries, idempotent loads, and making the whole stack reproducible with one `docker compose up`.
`Kafka` `Spark` `Airflow` `MinIO` `Snowflake` `Docker`

### [Demand Forecasting & Dynamic Pricing](https://github.com/Jaivinay/AI-Driven-Demand-Forecasting)
Multi-store, multi-SKU sales forecasting on Walmart's M5 dataset using a Temporal Fusion Transformer, with a PPO agent recommending prices on top of the forecast.
*The interesting part:* the pricing agent is only as good as the demand model underneath it — most of the work was making the forecast trustworthy before letting RL touch it.
`PyTorch` `Temporal Fusion Transformer` `PPO` `Reinforcement Learning`

### [Deepfake Image Detection](https://github.com/Jaivinay/deepfake-image-detection)
Real vs. fake image classification across ~190k images, comparing a CNN against a transformer.
*The interesting part:* Xception beat ViT here ([X]% vs [Y]% test accuracy) — transformers need more data than this to earn their keep, which is a more useful finding than picking the winner.
`TensorFlow` `PyTorch` `Xception` `Vision Transformer`

---

## Toolkit

**Languages** — Python, SQL, Java, R
**Data engineering** — Spark, Snowflake, AWS, Azure, GCP, Airflow, dbt, Databricks
**ML** — PyTorch, TensorFlow, scikit-learn, MLflow
**AI & agents** — LLM, LangChain, LlamaIndex, RAG, Vector Dtabases, MCP, Hugging Face, Ollama, OpenAI, AI Tools
**Shipping** — Docker, FastAPI, Streamlit, Git, GitHub Actions

---

<p align="center">
  <i>Happy to talk about any of the above — the failures more than the results.</i>
</p>
