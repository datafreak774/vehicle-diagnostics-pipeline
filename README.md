# 🚗 Vehicle Diagnostics Pipeline

> Real-time vehicle health monitoring and failure prediction system using streaming data.

## 🧠 Project Overview

This ongoing project simulates and processes real-time vehicle diagnostics data (synthetic data) using a modern big data stack. The goal is to build an end-to-end pipeline for real-time ingestion, processing, storage, and analytics of automotive health metrics — enabling proactive fault detection and predictive maintenance.

## ⚙️ Tech Stack (Planned)

- **Apache Kafka** – Data ingestion (Docker, Bitnami images)
- **Spark Streaming (PySpark)** – Real-time processing
- **Databricks / Local Spark** – Data engineering and ML model deployment
- **MinIO (S3-compatible)** – Object storage (data lake)
- **PostgreSQL** – Metadata and processed results storage
- **Apache Airflow** – Orchestration of data pipelines
- **Power BI / Plotly Dash** – Visualization of vehicle health & failure predictions
- **ML Models** – Anomaly detection & failure prediction from diagnostics data

## 🧱 Planned Architecture
[Kafka Producer] --> [Kafka Broker] --> [Spark Streaming (PySpark)] --> [MinIO Data Lake] --> [ML Model] --> [PostgreSQL] --> [Dashboard (Power BI / Dash)] ↘ [Airflow ETL Pipelines]


## 🚧 Current Status

> Project under development. Environment setup and initial data simulation in progress.

## 📌 Goals

- Simulate real-world diagnostics data streams
- Build scalable data pipeline using Spark + Kafka
- Train ML model to detect failures based on streaming data
- Store outputs in PostgreSQL, orchestrated via Airflow
- Deploy interactive dashboard for visualization

## 📅 Timeline

| Phase | Description | ETA |
|-------|-------------|-----|
| ✅ 1. Setup & Planning | Tech stack finalized, project scoped | Apr 2025 |
| 🔄 2. Data Simulation + Ingestion | Kafka stream with mock diagnostics data | Apr–May 2025 |
| 🔲 3. Real-time Processing + ML | Spark Streaming pipeline + failure prediction | May 2025 |
| 🔲 4. Visualization & Insights | Dashboard for health, faults, predictions | May–Jun 2025 |

---

📌 **Note:** This project is being actively developed and will be updated regularly. Feel free to ⭐ the repo and follow along. 

---
---

## UPDATE_1 : ( 💻 Project Status: In Progress )

Key components have been set up and tested:

Synthetic Data Generator: Python script simulating vehicle data (e.g., engine temp, RPM, error codes).

Apache Kafka: Dockerized Kafka for streaming data.

Spark Structured Streaming: Ingesting and processing data with PySpark, saving results to local files (parquet).

ML Model: Random Forest Classifier trained to predict vehicle failures with 98.67% accuracy on a small test dataset.

Visualization: Basic failure predictions visualized using Plotly (Power BI integration upcoming).

<img width="1432" alt="image" src="https://github.com/user-attachments/assets/ca0ad26d-62d5-46a5-a1a9-bd64fcd45e72" />

<img width="1431" alt="image" src="https://github.com/user-attachments/assets/69abdcd0-1bbc-46b2-b4d4-3ea0b7f2a61c" />

<img width="1431" alt="image" src="https://github.com/user-attachments/assets/9136149a-8da0-4246-9f26-4209cc42031e" />

<img width="1434" alt="image" src="https://github.com/user-attachments/assets/63be861b-c076-4ad2-b8d3-1c45f42fe92a" />

Note: The project is functional but still in progress. Final deployment and enhancements are underway!



