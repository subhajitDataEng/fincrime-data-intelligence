# 🚀 FinFlow – A Modern FinTech Platform Built by Two Founders
### 👩‍💼 CEO: Kimmi | 👨‍💻 CTO: Subhajit  
*A real-world end-to-end Data Engineering & AML Detection Project*

---

## 🧩 Overview

**FinFlow** is a digital payments and financial services startup co-founded by **Kimmi (CEO)** and **Subhajit (CTO)**.  
The company is built with a shared vision of creating a **secure, scalable, and compliant fintech platform**.

This repository showcases the **complete data engineering backbone** of FinFlow, designed and implemented to support:
- Real-time payments  
- Fraud detection & AML compliance  
- Business intelligence & executive reporting  

---

## 👩‍💼👨‍💻 Founders’ Story

FinFlow is built by two co-owners who share both **life and work**.

- **Kimmi (CEO)** drives the product vision, compliance strategy, partnerships, and growth.
- **Subhajit (CTO)** architects and builds the technology platform that turns that vision into reality.

We share the same workspace, solve problems together, and grow the startup side by side — combining vision and execution.

---

## 🏛️ Architecture Overview

FinFlow follows a **modern Lakehouse architecture**.

| Component | Description |
|---------|-------------|
| Azure Data Factory | Pipeline orchestration |
| Databricks (PySpark) | ETL & business logic |
| Delta Lake | Bronze, Silver, Gold layers |
| Azure SQL / MySQL | Metadata & reference data |
| TigerGraph | Graph-based AML detection |
| Power BI | CEO & executive dashboards |

---

## 🥉 Bronze Layer – Raw Data

Contains raw, unprocessed ingested data:
- `users.csv`
- `transactions.csv`
- `merchants.csv`
- `device_logs.csv`
- `login_activity.json`

📌 No transformations are applied at this stage.

---

## 🥈 Silver Layer – Cleansed & Validated Data

Key transformations:
- Schema enforcement  
- Timestamp standardization  
- Null & duplicate handling  
- Data quality checks  
- PII masking (email, phone)  
- KYC validation  

---

## 🥇 Gold Layer – Business & Analytics Data

Business-ready datasets used for:
- Daily transaction KPIs  
- Revenue analytics  
- User & merchant risk scoring  
- AML alert generation  
- Executive dashboards  

---

## 🔎 AML & Fraud Detection Rules

### 1️⃣ Velocity Anomaly Detection  
Flags unusually high transaction frequency.

### 2️⃣ Smurfing Detection  
Identifies multiple small deposits followed by a large withdrawal.

### 3️⃣ Device Change Risk  
High-value transactions from new or suspicious devices.

### 4️⃣ Merchant Risk Clustering  
Detects abnormal merchant transaction patterns.

### 5️⃣ Graph-based Fraud Ring Detection (TigerGraph)  
Uncovers:
- Connected suspicious users  
- Shared devices  
- Linked merchants  
- Multi-hop laundering networks  

---

## 🧠 CTO Responsibilities (Technology Execution)

- End-to-end PySpark pipelines  
- Metadata-driven ingestion framework  
- Delta Lake schema & partitioning  
- AML & fraud logic implementation  
- ADF pipeline orchestration  
- TigerGraph schema & GSQL queries  
- Scalable and audit-ready architecture  

---

## 👩‍💼 CEO Responsibilities (Vision & Strategy)

- Product roadmap & feature prioritization  
- AML & compliance rules definition  
- Risk threshold approvals  
- KPI reviews & decision-making  
- Investor communication & growth strategy  

The CEO defines the direction.  
The CTO builds the engine.

---

## 📈 CEO Dashboard (Power BI)

Includes:
- Total transactions & revenue  
- Suspicious transaction trends  
- Top risky users & merchants  
- AML alerts by category  
- Daily & monthly business KPIs  

---

## 🗂️ Repository Structure

