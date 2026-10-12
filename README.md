# Baran Ozgur Tas

![AI Engineer](https://img.shields.io/badge/AI_Engineer-8B5CF6?style=for-the-badge)
![Data Scientist](https://img.shields.io/badge/Data_Scientist-0891B2?style=for-the-badge)
![Data Engineer](https://img.shields.io/badge/Data_Engineer-059669?style=for-the-badge)

🎓 **MSc candidate in Artificial Intelligence at the University of Zurich** 

I bring **4+ years of combined professional and research experience** across AI, machine learning, and data engineering. I build **AI agents, agentic workflows, and RAG systems**, alongside predictive models and forecasting applications. My work combines **tool use, human-in-the-loop approval, and auditable execution** with systematic LLM evaluation, backed by industry experience building reliable data pipelines and software systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://linkedin.com/in/barantas)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:baranozgur.tas@gmail.com)

---

## 🧠 AI Engineering

*Retrieval systems and evaluation of model behaviour.*

### [Scholar-RAG](https://github.com/baranozgurtas/scholar-rag) | Research-paper question answering

Combines dense and sparse retrieval through reciprocal rank fusion, cross-encoder reranking, and citation validation to answer questions over academic literature. A FastAPI evidence UI connects answers to retrieved passages.

**Evaluation:** on a 35-question benchmark with fixed dev/held-out splits, hybrid retrieval with reranking retrieved every required source for **13 of 14 held-out answerable questions**. Results are exploratory given the small sample.

![BGE-M3](https://img.shields.io/badge/BGE--M3-7C3AED?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square)

### [LLM Judge Audit](https://github.com/baranozgurtas/llm-judge-audit) | Evaluating the evaluator

Audits an LLM judge against human preferences, examining answer-order sensitivity and associations between answer length and verdicts. Includes resumable inference, confidence intervals, and an interactive results dashboard.

**Finding:** audited **Gemma 3 4B** across **400 judgments on 200 human-labelled pairs**; swapping answer order changed verdicts for **57 pairs (28.5%)**.

![Ollama](https://img.shields.io/badge/Ollama-475569?style=flat-square)
![LLM Evaluation](https://img.shields.io/badge/LLM_Evaluation-7C3AED?style=flat-square)
![Statistical Analysis](https://img.shields.io/badge/Statistical_Analysis-0891B2?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square)

---

## 📊 Data Science

*Predictive models evaluated against realistic decision settings.*

### [TimeFlow](https://github.com/baranozgurtas/timeflow) | Forecasts to inventory decisions

Demand forecasting across **500 store–item time series**, combining LightGBM forecasts, calibrated prediction intervals, and a cost-aware stocking policy.

**Result:** reduced test SMAPE from **17.04% to 11.67%** versus a seasonal-naive baseline; achieved **89.13% empirical coverage** for a 90% prediction-interval target.

![LightGBM](https://img.shields.io/badge/LightGBM-059669?style=flat-square)
![Conformal Prediction](https://img.shields.io/badge/Conformal_Prediction-0891B2?style=flat-square)
![Quantile Regression](https://img.shields.io/badge/Quantile_Regression-7C3AED?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square)

### [London Spatial House Prices](https://github.com/baranozgurtas/london-spatial-house-prices) | Testing geographic generalisation

Models **375k London property sales** and compares random and spatial cross-validation to examine how evaluation design changes estimated performance.

**Analytical focus:** spatial validation, residual autocorrelation, SHAP explanations, and prediction uncertainty.

![LightGBM](https://img.shields.io/badge/LightGBM-059669?style=flat-square)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square)
![PySAL](https://img.shields.io/badge/PySAL-0891B2?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-BE185D?style=flat-square)

---

## ⚙️ Data Engineering

*Batch and streaming pipelines with explicit recovery and quality controls.*

### [MarketPulse](https://github.com/baranozgurtas/marketpulse-data-platform) | Batch analytics platform

Orchestrates data ingestion and PySpark processing into a Snowflake warehouse, with dbt transformations across **raw, staged, and curated** layers, idempotent processing, and data-quality checks.

**Data quality:** reduced **3,400 raw price records to 3,390 deduplicated rows**; dbt validation identified **one zero-price record**, prompting a staging fix that left **3,389 curated records**.

![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square)

### [Wiki Stream Pipeline](https://github.com/baranozgurtas/wiki-stream-pipeline) | Live event processing

Streams Wikipedia edits through Kafka / Redpanda into PostgreSQL, with idempotent writes, two-tier dead-letter handling, and Dagster-orchestrated data-quality checks.

**Idempotency:** a database integration test replays a **3-event batch three times** and asserts that only **3 rows** remain.

![Kafka / Redpanda](https://img.shields.io/badge/Kafka_%2F_Redpanda-E14226?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square)
![Dagster](https://img.shields.io/badge/Dagster-654FF0?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square)

---

## 🧰 Technical Toolkit

**Core:** Python · SQL · PostgreSQL · Oracle PL/SQL · T-SQL

**AI & ML:** PyTorch · scikit-learn · LightGBM · XGBoost · Hugging Face · Qdrant

**Data Platforms:** Airflow · Dagster · PySpark · dbt · Snowflake · AWS

**Delivery & Monitoring:** FastAPI · Docker · GitHub Actions · MLflow · Langfuse · Prometheus

---

📫 **Connect:** [LinkedIn](https://linkedin.com/in/barantas) · [baranozgur.tas@gmail.com](mailto:baranozgur.tas@gmail.com)
