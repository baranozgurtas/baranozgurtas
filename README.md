# Hi, I'm Baran 👋

Data professional with 4+ years of industry experience taking ML models from prototype to production, owning the full lifecycle from data ingestion through deployment and monitoring.

🎓 MSc candidate in **Artificial Intelligence at the University of Zurich**, with a joint master's project at **ETH Zurich**.

📍 Based in Zurich, open to relocation across the EU and UK.

I work across three tracks: **Data Science** (predictive modelling, time-series forecasting, statistical evaluation), **ML Engineering** (RAG systems, model serving, MLOps and observability), and **Data Engineering** (streaming and batch data pipelines). The projects below are grouped that way.

---

## 🔬 Data Science

- **[london-spatial-house-prices](https://github.com/baranozgurtas/london-spatial-house-prices)** — Spatial ML on 375k real London house sales. Proves that random cross-validation leaks neighbourhood signal (R² 0.70) and measures the honest generalisation gap with spatial CV (R² 0.38), with Moran's I, SHAP, conformal intervals, and residual maps. *LightGBM, GeoPandas, PySAL, SHAP.*
- **[timeflow](https://github.com/baranozgurtas/timeflow)** — End-to-end demand forecasting with LightGBM point and quantile models, conformalized prediction intervals, and a newsvendor policy layer that turns forecasts into stocking decisions. *LightGBM, conformal prediction, Streamlit.*

## 🤖 ML Engineering

- **[scholar-rag](https://github.com/baranozgurtas/scholar-rag)** — Production RAG over academic literature: hybrid retrieval (BGE-M3 dense + sparse + RRF), cross-encoder reranking, and citation validation. Lifts MRR@10 from 0.925 to 0.967 and abstains correctly on 5/5 out-of-corpus queries, with full Langfuse + Prometheus observability. *LangChain, Qdrant, FastAPI, Docker, GitHub Actions.*
- **[job-intelligence-api](https://github.com/baranozgurtas/job-intelligence-api)** — ML-powered API that classifies job postings into ML Engineer, Data Engineer, and Data Scientist roles and extracts structured skill tags. *FastAPI, MLflow, Docker, CI/CD.*

## 🛠️ Data Engineering

- **[wiki-stream-pipeline](https://github.com/baranozgurtas/wiki-stream-pipeline)** — Real-time streaming pipeline: live Wikipedia edits through Kafka (Redpanda) into Postgres, built for reliability with idempotent delivery, two-tier dead-letter queues, a failure taxonomy, and Dagster-orchestrated data-quality checks. *Kafka, Postgres, Dagster, Docker.*
- **[marketpulse-data-platform](https://github.com/baranozgurtas/marketpulse-data-platform)** — Batch data platform with Airflow orchestration, PySpark feature computation, and a Snowflake medallion warehouse (RAW → STAGED → CURATED), with idempotent deduplication and quality gates. *Airflow, PySpark, Snowflake, dbt.*

---

## 🧰 Tech

**Data Science:** LightGBM · XGBoost · scikit-learn · PyTorch · SHAP · GeoPandas · PySAL · Prophet · conformal prediction

**ML Engineering:** LangChain · Qdrant · Hugging Face · FastAPI · MLflow · Langfuse · Prometheus · Docker · GitHub Actions

**Data Engineering:** Kafka / Redpanda · PySpark · Airflow · Dagster · Snowflake · PostgreSQL · dbt · AWS

**Languages:** Python · SQL (PostgreSQL, Oracle PL/SQL, T-SQL)

---

📫 Reach me: [LinkedIn](https://linkedin.com/in/barantas) · baranozgur.tas@gmail.com
