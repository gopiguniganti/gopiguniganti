# Hey, I'm Gopi 👋

Senior Data Engineer with 5+ years building the AML and financial-crimes
data platform behind a major bank's transaction monitoring and regulatory
reporting — production Spark on AWS EMR, AWS Glue serverless pipelines,
Airflow (MWAA) orchestration, and SSIS/Netezza. Outside of that, I use
personal projects to go deeper on tools I don't touch day-to-day —
currently Databricks/Delta Lake and dbt — plus some self-hosted
infrastructure.

---

## 💼 Professional focus

AML transaction monitoring and regulatory reporting (FINTRAC, FinCEN) for a
major bank — Spark on AWS EMR, AWS Glue/Lambda serverless pipelines, 200+
production Airflow DAGs, SSIS/Netezza.

## 📊 Personal projects — data engineering

### Sanctions Screening Pipeline — Databricks / Delta Lake
A self-directed project to get hands-on with Databricks/Delta Lake outside
my day job's EMR/Glue stack. Bronze/silver/gold pipeline that ingests the
OFAC sanctions list, cleans and upserts it into Delta (`MERGE INTO`,
`OPTIMIZE`/`ZORDER BY`, time travel), and screens a customer list against
it with a fuzzy-match scorer.

→ [gopiguniganti/sanctions_pipeline](https://github.com/gopiguniganti/sanctions_pipeline)

### Transaction Data Quality — dbt
A dbt project that models raw transaction data into analytics-ready marts
and enforces data quality with schema tests and a custom source-to-target
reconciliation check (row count + amount parity between raw and curated
data). Runs fully locally on DuckDB.

→ [gopiguniganti/Dbt_transaction_quality](https://github.com/gopiguniganti/Dbt_transaction_quality)

---

## 🛠️ Other projects

### HomeLab
Personal HomeLab with 40+ Docker containers on a home server covering media,
backups, documents, local AI, finance, fitness, and monitoring.

→ [gopiguniganti/HomeLab](https://github.com/gopiguniganti/HomeLab)

- 🤖 Local AI with [Open WebUI](https://github.com/open-webui/open-webui)
- 📸 [Immich](https://immich.app/) for self-hosted photo backups and organization
- 📄 [Paperless-ngx](https://docs.paperless-ngx.com/) for OCR and document management
- ⚙️ [n8n](https://n8n.io/) for personal workflow automation
- 🔍 [SearXNG](https://searxng.github.io/searxng/) for private search
- 📊 Monitoring and visibility with ntopng, Scrutiny, and dashboard tooling

### Real-Time Car Telemetry
A local telemetry pipeline for my car that reads OBD-II data over
Bluetooth, streams it into InfluxDB, and visualizes it in Grafana — speed,
engine load, coolant temperature, fuel trims, and other real-time
diagnostics. Packaged with Python and Docker Compose.

→ [gopiguniganti/realtime-telemetry-pipeline](https://github.com/gopiguniganti/realtime-telemetry-pipeline)

---

## 🧰 Tools I use

**Day job:**

![Apache Spark](https://img.shields.io/badge/PySpark%2FScala-E25A1C?style=flat&logo=apachespark&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Personal projects:**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat&logo=delta&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat&logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)

---

📍 Toronto, ON
