# kafka_Practice

# Kafka Producer & Consumer with Confluent Cloud (Python)

This project demonstrates an **end-to-end Kafka streaming pipeline** using **Python** and **Confluent Cloud**.  
Customer data is read from a CSV file, converted to JSON, produced to a Kafka topic, and consumed in real time.

---

## Architecture Flow

CSV → JSON → Kafka Producer → Kafka Topic (`ecommerce`) → Kafka Consumer → Console Output

This simulates a **real-world event-driven data pipeline** commonly used in **data engineering and streaming systems**.

---

## Tech Stack

- Python 3
- Apache Kafka (Confluent Cloud)
- confluent-kafka
- Pandas
- JSON

---

Features

Secure Kafka connection using SASL_SSL

JSON-based message serialization

Delivery acknowledgment handling

Consumer groups & offset management

Real-time streaming pipeline

