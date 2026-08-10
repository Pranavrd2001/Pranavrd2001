# 👋 Pranav R Deshkulkarni

**Backend Engineer · Distributed Systems · Event-Driven Architecture · Java**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

---

## About

Backend engineer with 3.5+ years at **Gainsight**, building event-driven distributed systems in Java.
I design and own backend systems end-to-end — from architecture and data modelling to production rollout.

Most recently: sole architect of Gainsight's **EventStream Connector** — a real-time Kafka pipeline
with durable event replay and recovery. Currently leading a platform-wide migration from legacy AES
to **AWS KMS encryption** across 16 services, accelerated by a Claude Code skill I authored to automate the migration pattern.

---

## Things I've built

**⚡ EventStream Connector — Real-time Kafka Pipeline**
> Designed and built ground-up. Replaced batch sync jobs with a real-time event-driven framework — consumer partitioning, UPSERT semantics, idempotent processing, and a durable replay system for zero-touch failure recovery.
> `Java` `Spring Boot` `Apache Kafka` `PostgreSQL`

**🔐 Platform-wide KMS Credential Migration**
> Migrating 16 services from legacy AES to AWS KMS. Refactored monolithic switch-case CRUD into per-service impl classes; redesigned I/O DTOs; enforced zero-credential API responses. Authored a Claude Code skill to automate the pattern — first 2 manual, next 14 automated.
> `Java` `AWS KMS` `Spring Boot` `Claude Code`

**📦 Multipart S3 Upload — Shared Core Library**
> Implemented multipart upload in a shared core library to handle objects beyond AWS S3's 5 GB limit. Adopted by 3 independent backend services with zero per-service code changes. Triggered by a production OOM crash.
> `Java` `AWS S3`

**🗄️ Bulk Data Writeback Pipeline — SAP Datasphere**
> Full system design and implementation of an async batch pipeline: CSV ingestion → staging table → MERGE into SAP Datasphere. 14 data types, configurable batch sizes, 6M rows in ~6 min.
> `Java` `Spring Boot` `Async APIs`

---

## Currently

- 🟢 **Building:** KMS encryption migration across 16 services — live in production, zero major incidents so far
- 🔵 **Using:** Claude Code daily — authored 2 reusable skills to automate repetitive backend migration patterns  
- 🟡 **Exploring:** Open to backend / distributed systems SDE-2 roles at product-first companies

---

## Let's connect

📧 krrgpranavrd2001@gmail.com &nbsp;·&nbsp; 💼 [LinkedIn](YOUR_LINKEDIN_URL) &nbsp;·&nbsp; 📍 Bangalore, India

> ⚠️ Most of my production code lives in a private org repo (Gainsight). The projects above are real shipped systems — happy to walk through architecture in an interview.
