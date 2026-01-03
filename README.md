
---

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/110361282?s=400&v=4" width="110" height="110" style="border-radius: 50%;" />
</p>

<h2 align="center">Sanju</h2>
<p align="center"><strong>Data Engineer</strong> • Event-driven Streaming & Batch Data Pipelines</p>

---

## 👋 About Me

I am a Computer Science student with a strong focus on **Data Engineering**.

I build **reliable, production-style data pipelines** — from ingestion and orchestration to transformation and analytics-ready datasets — using modern tools commonly adopted in industry.

My work emphasizes:

* data reliability & idempotency
* clear pipeline architecture
* schema-aware ingestion
* batch **and** streaming systems

I also work with **stateful streaming pipelines** using Kafka and Spark, focusing on event-time processing, windowed aggregations, and failure-safe design.

---

## 🧱 Core Engineering Stack

* **Languages**: Python, SQL, Bash
* **Streaming**: Apache Kafka (Confluent, KRaft mode)
* **Streaming Processing**: Apache Spark Structured Streaming
* **Orchestration**: Apache Airflow
* **Transformation & Modeling**: dbt
* **Databases**: PostgreSQL, BigQuery
* **Visualization**: Grafana
* **Cloud**: Google Cloud Platform (GCS, BigQuery, Secret Manager)
* **Infrastructure**: Docker, Docker Compose
* **Data Quality**: Pydantic validation, dbt tests

---

## 🚀 Selected Projects

### 🔷 Realtime Crypto Streaming Pipeline — Kafka & Spark

**Stateful, event-driven streaming system**

* Ingests live trade events from Binance WebSocket
* Schema validation with Pydantic before Kafka publish
* Idempotent Kafka producer (at-least-once delivery)
* Spark Structured Streaming with event-time windows & watermarking
* Stateful OHLC aggregation (1-minute base candles)
* Multi-timeframe candles (5m, 15m, 45m, 1h) derived via PostgreSQL views
* Idempotent PostgreSQL sink using UPSERT + composite primary keys
* Real-time monitoring via Grafana dashboard

**Tech**: Kafka (KRaft), Spark Structured Streaming, PostgreSQL, Grafana, Docker
🔗 Repo: [https://github.com/S4njuuu3291/realtime-crypto-price-dashboard](https://github.com/S4njuuu3291/realtime-crypto-price-dashboard)

---

### 🌍 Global Commodity Data Platform — Airflow, GCP & dbt

**Production-style batch data platform**

* Multi-source ingestion (metals, FX, macro indicators, news)
* Raw data persisted in GCS (Bronze layer)
* BigQuery warehouse with layered modeling
* dbt staging → dimension → fact → mart
* Incremental models, schema evolution, and data tests

**Tech**: Airflow, GCP, BigQuery, dbt, Docker
🔗 Repo: [https://github.com/S4njuuu3291/phase4_global_commodity](https://github.com/S4njuuu3291/phase4_global_commodity)

---

### 🌦️ Weather ETL Pipeline — Python & PostgreSQL

**Foundational ETL & automation**

* API ingestion with clear Extract → Transform → Load separation
* Configuration-driven pipeline using YAML
* Logging & error handling
* Automated scheduling via Cron

**Tech**: Python, PostgreSQL, SQLAlchemy, Cron
🔗 Repo: [https://github.com/S4njuuu3291/porto-01-data-preprocessing](https://github.com/S4njuuu3291/porto-01-data-preprocessing)

---

## 🧠 Engineering Interests

* Event-driven architectures
* Stateful stream processing & event-time semantics
* Streaming vs batch trade-offs
* Data modeling & analytics-ready datasets
* Reliability, replayability, and failure handling

---

## 📌 Current Focus

Deepening expertise in **streaming systems**, **distributed data processing**, and **production-grade pipeline design**, with an emphasis on correctness, observability, and operational safety.

---

## 📬 Contact

* LinkedIn: [https://www.linkedin.com/in/sanjukin-pinem](https://www.linkedin.com/in/sanjukin-pinem)
* Email: [sanju329121@gmail.com](mailto:sanju329121@gmail.com)

---
