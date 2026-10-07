# 👋 Pranav R Deshkulkarni

**Senior Software Engineer · Distributed Systems · Event-Driven Data Infrastructure · Java**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

---

## About

Backend engineer with 4+ years at **Gainsight**, building event-driven and data-intensive systems in Java.
I own systems end-to-end, from architecture and data modelling to production rollout and recovery.
Promoted twice in 18 months (Associate SE → SE → Senior SE).

The problems I enjoy most sit at the core of distributed data systems: ordering, partitioning,
idempotency, durability, replay and recovery.

---

## Things I've built at work

**⚡ Real-time Event Sync Framework (Kafka)**
> Sole backend owner; designed and built from scratch. Replaced scheduled batch jobs with a real-time
> event-driven pipeline. Per-tenant ordering via partition keys, UPSERT semantics and idempotent consumers
> across multiple object types, and a durable replay system for recovery without manual intervention.
> Handles bursts of 6,000+ events in 2 minutes with no dropped events.
> `Java` `Spring Boot` `Apache Kafka` `PostgreSQL`

**🔐 AES → AWS KMS Envelope Encryption Migration**
> Sole owner, ongoing. Migrating 16 service connections from legacy AES to AWS KMS envelope encryption.
> Restructured a monolithic switch-case design into per-service implementations, introduced typed DTOs,
> and enforced zero-credential API responses. Migrated the first 2 by hand, then encoded the pattern as a
> reusable Claude Code skill for the remaining 14. Live in production, no major incidents.
> `Java` `AWS KMS` `Spring Boot`

**📦 Streaming Multipart Upload: Shared Core Library**
> Multipart upload for objects beyond Amazon S3's 5 GB single-upload limit, streamed rather than buffered
> in memory. Fixed a production out-of-memory crash and was adopted by 3 services with no per-service changes.
> `Java` `AWS S3`

**🗄️ Bulk Data Writeback Pipeline: SAP Datasphere**
> Async batch pipeline: CSV ingestion → staging table → MERGE into SAP Datasphere. Insert/update/upsert
> across 14 data types; 6M rows in ~6 min, 5 GB in ~15 min.
> `Java` `Spring Boot` `SQL`

> ⚠️ My production code lives in Gainsight's private repositories. Happy to walk through the architecture of any of these.

---

## Research & academic work

- 📄 **Publication:** *Adaptive Ambulance Monitoring System using IoT (Detecting Ambulance by Camera)*,
  Measurement: Sensors, vol. 24, 2022 · [Read on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2665917422001891)
  Built the ambulance-side embedded unit (Arduino, sensors, RF transmission) and the hospital-side Android app.
- 🗃️ [DBMS Mini Project: Billing System](https://github.com/Pranavrd2001/DBMS-Mini-Project---Billing-System),
  a store billing and sales-records application (C#, SQLite).
- 📁 [File Structures Mini Project: General Ledger](https://github.com/Pranavrd2001/General-Ledger-Problem-using-cosequential-processing---File-Structures-Mini-Project),
  a general-ledger posting system using cosequential processing.

---

## Currently

- 🟢 **Building:** the KMS envelope-encryption migration across 16 service connections
- 📚 **Preparing for:** graduate study (MS in Computer Science, Fall 2027) in distributed and data systems

---

## Let's connect

📧 krrgpranavrd2001@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/pranav-r-d-198a321b4) · 📍 Bengaluru, India
