
---

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/110361282?s=400&v=4" width="110" height="110" style="border-radius: 50%;" />
</p>

<h2 align="center">Sanju</h2>
<p align="center"><strong>Data Engineer</strong> • Event-driven Streaming & Batch Data Pipelines</p>

---

## 👋 About Me

Computer Science student focused on **Data Engineering** — building reliable, production-grade data pipelines from ingestion to analytics-ready datasets.

**Core Principles**:
* **Production Engineering**: Type-safe code (Pydantic), 115+ tests, custom exception handling
* **Data Reliability**: Schema validation, idempotent operations, quality checks
* **Architecture**: Layered design (Bronze/Silver/Gold), modular & config-driven
* **Streaming & Batch**: Event-time processing, stateful aggregations, incremental transforms
* **Quality Assurance**: Unit/integration/E2E tests, structured logging, monitoring

---

## 🧱 Core Engineering Stack

* **Languages**: Python 3.12+, SQL, Bash
* **Streaming**: Apache Kafka (Confluent, KRaft), Avro serialization | Spark Structured Streaming
* **Batch Orchestration**: Apache Airflow 3.1+ (TaskFlow API)
* **Transformation**: dbt 1.8+ (incremental models, tests)
* **Databases**: PostgreSQL, BigQuery (partitioned & clustered)
* **Cloud**: AWS (Lambda, S3, ECR, Glue, EventBridge, Athena) | GCP (GCS, BigQuery, Secret Manager)
* **IaC & DevOps**: Terraform, Docker, GitHub Actions
* **Data Quality**: Pydantic v2, Pandera, dbt tests, custom exceptions
* **Testing**: pytest (115+ tests), httpx mocking, E2E validation
* **Web Scraping**: Playwright (headless automation, anti-bot evasion)
* **Visualization**: Grafana
* **HTTP Clients**: httpx, tenacity (exponential backoff)

---

## 🚀 Selected Projects

### 🌐 Serverless Job Scraping Pipeline — AWS Lambda & Terraform

**Daily automated web scraping with IaC deployment**

* Scrapes 3 Indonesian job platforms (Kalibrr, Glints, JobStreet) via **Playwright headless browsers**
* **Anti-bot evasion**: Stealth plugins, navigator.webdriver removal, custom user agents
* **Data validation** with Pandera schemas before storage
* **Partitioned Parquet files** in S3 (Bronze layer: `platform=/ingestion_date=/`)
* **AWS Glue catalog** → Athena SQL queries for analytics
* **EventBridge scheduler** triggers daily at 5 AM WIB
* **4-stage CI/CD pipeline**: test → Terraform provision → Docker build → Lambda deploy
* **Serverless architecture**: ~200 jobs/day, $0.15-0.80/month (within free tier)
* **Performance optimizations**: Lazy imports, async I/O, resource blocking, exponential backoff

**Tech**: AWS (Lambda, S3, ECR, Glue, EventBridge), Terraform, Python 3.12, Playwright, Pandera, PyArrow, GitHub Actions
🔗 Repo: [https://github.com/S4njuuu3291/job-data-pipeline](https://github.com/S4njuuu3291/job-data-pipeline)

---

### 🔷 Realtime Crypto Streaming Pipeline — Kafka & Spark

**Stateful event-driven streaming with Avro serialization**

* Live trade ingestion from Binance WebSocket → Pydantic validation → Kafka (20 partitions, KRaft mode)
* **Avro serialization** with Confluent Schema Registry for type safety
* **Idempotent producer** (acks=all, at-least-once delivery)
* **Spark Structured Streaming**: event-time windows, watermarking, stateful OHLC aggregation
* Multi-timeframe candles (1m, 5m, 15m, 45m, 1h) via PostgreSQL views
* **Idempotent sink**: UPSERT with composite primary keys
* Grafana dashboard with real-time candlestick visualization
* Fault-tolerant with checkpointing

**Tech**: Kafka (Confluent, KRaft), Avro, Spark Structured Streaming, PostgreSQL, Grafana, Docker
🔗 Repo: [https://github.com/S4njuuu3291/realtime-crypto-price-dashboard](https://github.com/S4njuuu3291/realtime-crypto-price-dashboard)

---

### 🌍 Global Commodity Data Platform — Airflow, GCP & dbt

**Production batch platform with comprehensive testing**

* **115 unit + integration tests** (100% passing) with pytest
* Multi-source ingestion: metals, FX, macro indicators, news APIs
* **Type-safe Pydantic v2 models** + **custom exception hierarchy** (8 types)
* **Tenacity retry logic** with exponential backoff for API resilience
* GCS Bronze layer (date-partitioned NDJSON) → **BigQuery warehouse**
* **11 dbt incremental models**: staging → dimension → fact → mart (SAFE_CAST for data quality)
* E2E validation pipeline with schema/quality/relationship tests
* Environment-based config (.env + GCP Secret Manager)

**Tech**: Airflow 3.1.3 (TaskFlow API), GCP (BigQuery, GCS), dbt 1.8+, Pydantic v2, pytest, Docker
🔗 Repo: [https://github.com/S4njuuu3291/phase4_global_commodity](https://github.com/S4njuuu3291/phase4_global_commodity)

---

## 🧠 Engineering Interests

* Production code quality: type safety, comprehensive testing, error handling
* Event-driven architectures & pub/sub patterns
* Stateful stream processing & event-time semantics
* Data modeling & dimensional design (SCD, star schema)
* Reliability: idempotency, retry mechanisms, circuit breakers
* Data quality frameworks: validation, contracts, quality checks
* Observability, replayability & failure handling

---

## 📌 Current Focus

Deepening expertise in **streaming systems**, **distributed processing**, and **production-grade pipelines**:

* **Code quality**: Type-safe Python (Pydantic), comprehensive test coverage (unit/integration/E2E)
* **Reliability**: Custom exceptions, exponential backoff, idempotent operations
* **Modern orchestration**: Airflow TaskFlow API, dynamic DAG generation
* **Cloud-native patterns**: AWS & GCP, infrastructure as code (Terraform)
* **Data modeling**: dbt incremental models, dimensional design, quality tests
* **Serverless architectures**: AWS Lambda, event-driven ETL, cost optimization

---

## 📬 Contact

* LinkedIn: [https://www.linkedin.com/in/sanjukin-pinem](https://www.linkedin.com/in/sanjukin-pinem)
* Email: [sanju329121@gmail.com](mailto:sanju329121@gmail.com)

---
