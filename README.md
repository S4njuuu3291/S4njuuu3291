
---

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/110361282?s=400&v=4" width="110" height="110" style="border-radius: 50%;" />
</p>

<h2 align="center">Sanju</h2>
<p align="center"><strong>Data Engineer</strong> • Building Resilient, Type-Safe Data Pipelines with 115+ Comprehensive Tests</p>

---

## 👋 About Me

Data Engineer specializing in **reliable, production-grade systems**. Building with Contract-Driven Development (Pydantic v2), defensive coding practices, and 115+ automated tests to ensure data integrity across AWS and GCP.

Philosophy: **Resilience > Convenience**. Choose technologies that guarantee data safety, not shortcuts.

---

## 🧱 Core Stack

**Orchestration** | Python 3.12+, Airflow 3.1.3, AWS Step Functions, Terraform

**Streaming** | Kafka (KRaft, Confluent Schema Registry), Spark Structured Streaming, Avro

**Data** | BigQuery, PostgreSQL 16, dbt 1.8+

**Reliability** ⭐ | Pydantic v2, pytest (115+ tests), Tenacity, custom exceptions

**Cloud** | AWS (Lambda, S3, Step Functions, EventBridge, Glue, Athena, ECR) | GCP (BigQuery, GCS, Secret Manager)

**DevOps** | Docker, GitHub Actions, Playwright

---


## �🚀 Featured Projects (Top 3)

### 🌐 Serverless Job Scraping Pipeline — AWS Lambda & Terraform

**Production medallion ETL: parallel scrapers (3x) → Silver validation → Slack alerts**

* **Parallel Step Functions**: 60% speedup (135s → 54s) with 3 concurrent Lambda scrapers
* **Medallion architecture**: Bronze → Silver (19-field Pydantic schema, MD5 dedup) → Query (Athena)
* **Auto-categorization**: NEW vs RE-POST jobs with 7-day lookback
* **Slack notifications**: Block Kit alerts (9 AM & 4 PM WIB)
* **Reliability**: DLQ, 2-attempt retry, exponential backoff

**Metrics**: ~65s end-to-end | 100% Pydantic validation | 4-stage CI/CD (pytest → Terraform → ECR → Lambda)

🔗 [job-data-pipeline](https://github.com/S4njuuu3291/job-data-pipeline)

---

### 🌍 Global Commodity Data Platform — Airflow, GCP & dbt

**Batch pipeline: multi-source APIs → GCS Bronze → BigQuery + 11 dbt models. 115+ test coverage.**

* **Multi-source ingestion**: Metals APIs, FX rates, macro indicators (Pydantic v2 validation)
* **115+ pytest cases**: Unit, integration, E2E across all transformation layers
* **8 custom exceptions**: Precise error classification and recovery
* **BigQuery warehouse**: 11 dbt incremental models (staging → dimension → fact → mart)
* **Data quality gates**: SAFE_CAST, dbt tests (relationships, uniqueness), Secret Manager creds

**Metrics**: 115+ tests | 3-layer medallion (Bronze/Silver/Gold) | 11 dbt models

🔗 [phase4_global_commodity](https://github.com/S4njuuu3291/phase4_global_commodity)

---

### 🔷 Realtime Crypto Streaming Pipeline — Kafka & Spark

**Event-driven: Binance WebSocket → Kafka → Spark aggregation → PostgreSQL → Grafana**

* **Idempotent producer**: acks=all, at-least-once delivery with deduplication
* **Avro schema registry**: Type-safe schema evolution via Confluent
* **Spark Structured Streaming**: Event-time windows, watermarking, stateful OHLC (1m, 5m, 15m, 45m, 1h)
* **Idempotent sink**: UPSERT on composite keys (symbol, timeframe, open_time)
* **Fault tolerance**: Checkpointing, recovery, event replay

**Reliability**: At-least-once with idempotent sink | Watermarking enabled | State checkpointing

🔗 [realtime-crypto-price-dashboard](https://github.com/S4njuuu3291/realtime-crypto-price-dashboard)

---

## 📦 Other Projects

**Also built:** Metal Price ETL (Airflow) • Weather ETL (Cron) • Metal Price GCP (BigQuery) • Gold Price Slack Alerts • Real-Time Sales Analytics • CI/CD Learning  
*3 featured systems above cover 90% of engineering depth.*

---

## 📊 Project Statistics

| Metric | Achievement |
|--------|-------------|
| **Comprehensive Tests** | 115+ cases (pytest) |
| **Cloud Platforms** | 2 (AWS & GCP) |
| **Pipelines** | 3 featured + 6 additional |
| **Orchestration** | Airflow 3.1.3 & AWS Step Functions |
| **Data Warehouses** | PostgreSQL 16 & BigQuery |
| **dbt Models** | 11 (incremental, fully tested) |
| **Streaming Tech** | Kafka (KRaft) & Spark Structured Streaming |
| **CI/CD Integration** | 100% Automated (GitHub Actions) |

---

## 🧠 Philosophy

**What I've Proven** | Resilience > Convenience • Testing is insurance (115+ tests) • Event-time semantics matter (watermarking, late data) • Idempotency at scale prevents data corruption

**Focus Areas** | Exactly-once processing • Data quality as first-class • Serverless reliability patterns • Multi-cloud consistency • Type-safe pipelines (Pydantic v2)

---

## 📌 Current Work

**Now** | Spark Structured Streaming internals • Redpanda (lower-latency alternative to Kafka) • Data quality frameworks (anomaly detection, SLA monitoring) • Multi-cloud deployment patterns

---

## 📬 Contact & Links

* **GitHub**: [S4njuuu3291](https://github.com/S4njuuu3291)
* **LinkedIn**: [sanjukin-pinem](https://www.linkedin.com/in/sanjukin-pinem)
* **Email**: [sanju329121@gmail.com](mailto:sanju329121@gmail.com)

---
