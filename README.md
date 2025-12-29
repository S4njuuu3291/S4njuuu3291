<p align="center">
  <img src="https://avatars.githubusercontent.com/u/110361282?s=400&v=4" width="110" height="110" style="border-radius: 50%;" />
</p>

<h2 align="center">Sanju</h2>
<p align="center"><strong>Data Engineer</strong> • Event-driven & Batch Data Pipelines</p>

---

### 👋 About Me
I am a Computer Science student with a strong focus on **Data Engineering**.

I build **reliable, production-style data pipelines** — from ingestion and orchestration to transformation and analytics-ready datasets — using modern tools commonly adopted in industry.

My work emphasizes:
- data reliability & idempotency
- clear pipeline architecture
- schema-aware ingestion
- batch and streaming systems

---

### 🧱 Core Engineering Stack
- **Languages**: Python, SQL, Bash  
- **Streaming**: Apache Kafka (Confluent, KRaft mode)  
- **Orchestration**: Apache Airflow  
- **Transformation & Modeling**: dbt  
- **Databases**: PostgreSQL, BigQuery  
- **Cloud**: Google Cloud Platform (GCS, BigQuery, Secret Manager)  
- **Infrastructure**: Docker, Docker Compose  
- **Data Quality**: Pydantic validation, dbt tests  

---

### 🚀 Selected Projects

#### 🔷 Crypto Streaming Pipeline — Kafka & PostgreSQL  
**Real-time, event-driven data pipeline**

- Ingests live trade events from Binance WebSocket  
- Schema validation with Pydantic before Kafka publish  
- Kafka producer with idempotence enabled  
- Consumer commits offsets only after successful DB transaction  
- Idempotent PostgreSQL sink using composite primary keys  

**Tech**: Kafka (KRaft), Python, SQLAlchemy, PostgreSQL, Docker  
🔗 Repo: https://github.com/S4njuuu3291/crypto-streaming-pipeline

---

#### 🌍 Global Commodity Data Platform — Airflow, GCP, dbt  
**Production-style batch data platform**

- Multi-source ingestion (metals, FX, macro, news)  
- Raw data persisted in GCS (Bronze layer)  
- BigQuery warehouse with layered modeling  
- dbt staging → dimension → fact → mart  
- Incremental models, schema evolution, data tests  

**Tech**: Airflow, GCP, BigQuery, dbt, Docker  
🔗 Repo: https://github.com/S4njuuu3291/phase4_global_commodity

---

#### 🌦️ Weather ETL Pipeline — Python & PostgreSQL  
**Foundational ETL & automation**

- API ingestion with clean Extract → Transform → Load separation  
- Configuration-driven pipeline (YAML)  
- Logging & error handling  
- Automated scheduling via Cron  

**Tech**: Python, PostgreSQL, SQLAlchemy, Cron  
🔗 Repo: https://github.com/S4njuuu3291/porto-01-data-preprocessing

---

### 🧠 Engineering Interests
- Event-driven architectures  
- Streaming vs batch trade-offs  
- Data modeling & analytics-ready datasets  
- Reliability, replayability, and failure handling  

---

### 📌 Current Focus
Deepening expertise in **streaming systems**, **distributed data processing**, and **production-grade pipeline design**.

---

### 📬 Contact
- LinkedIn: https://www.linkedin.com/in/sanjukin-pinem  
- Email: sanju329121@gmail.com
