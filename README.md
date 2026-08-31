# Real-Time Fraud Detection Streaming Pipeline

This project builds a system that watches banking transactions as they happen and instantly flags ones that look suspicious, like unusual amounts or strange locations. It solves the problem of fraud teams finding out about bad transactions too late, after the damage is done. The pipeline processes high volumes of events quickly and reliably so alerts show up in near real time.

## Tech Stack
- Python
- Apache Kafka
- Kafka Connect
- Spark Structured Streaming
- Schema Registry
- Databricks
- Grafana
- Prometheus

## Directory Structure
- `producer/`: Kafka producers for generating transaction data.
- `consumer/`: Kafka consumers for reading processed alerts.
- `streaming/`: Spark Structured Streaming jobs for processing events.
- `fraud_engine/`: Rules and ML models for detecting fraud.
- `schemas/`: Avro/JSON schemas for topics.
- `connectors/`: Kafka Connect configurations.
- `monitoring/`: Grafana and Prometheus configurations.
- `infrastructure/`: IaC and deployment scripts.
- `tests/`: Unit and integration tests.
  
