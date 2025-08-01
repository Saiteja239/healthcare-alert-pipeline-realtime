# 🏥 Real-Time Healthcare Alerts Pipeline

A real-time data pipeline that simulates patient vitals ingestion using HL7/FHIR-style mock data. It uses Apache Kafka, PySpark, and a Snowflake-like database to detect abnormal health conditions and trigger alerts in near real-time.

---

## 🚀 Key Features

- Kafka Producer — Streams mock HL7/FHIR patient vitals (heart rate, oxygen level).
- PySpark Stream Processor — Reads from Kafka and transforms the data.
- Alert Engine — Detects anomalies (high heart rate, low oxygen).
- Simulated Snowflake Load** — Data is stored in a PostgreSQL/Snowflake-like database.
- Modular Codebase — Clean, extendable Python scripts.

---

## 🧰 Tech Stack

- Python
- Apache Kafka
- PySpark
- PostgreSQL (Snowflake simulation)
- Docker
- Git & GitHub

---

## 🧪 How It Works

