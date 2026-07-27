# 💳 FinPay — Financial Transaction & Customer Analytics

An end-to-end FinTech analytics solution featuring data cleaning and ETL processing in **Python**, relational data storage in **MySQL**, and executive interactive dashboards built in **Power BI**[cite: 1, 2, 3].

---

## 📌 Executive Summary
This project processes **50,000+ transaction records** and **5,000 customer profiles** to evaluate operational performance, customer segmentation, transaction health, and revenue drivers[cite: 2, 3].

### Key Performance Highlights:
- **Processed Volume:** ₹ 1.33M total volume (in filtered executive view)[cite: 1].
- **Customer Segmentation:** **Retail** customers drive the vast majority of volume (₹ 0.77M), followed by **Premium** (₹ 0.22M) and **SME** (₹ 0.16M)[cite: 1].
- **Top Financial Products:** **Loan EMIs** (₹ 0.48M) and **Direct Transfers** (₹ 0.35M) constitute the largest transaction types by monetary value[cite: 1].
- **Geographic Breakdown:** **Gujarat** (₹ 0.21M), **Karnataka** (₹ 0.17M), and **Maharashtra** (₹ 0.16M) emerge as top performing regions[cite: 1].
- **System Conversion Health:** **87.9%** Successful, **10.2%** Failed, and **1.9%** Pending transactions[cite: 1].

---

## 🏗️ Architecture & Data Pipeline

```text
Raw CSV Files ➔ Data Preprocessing (Python) ➔ Relational Storage (MySQL) ➔ Interactive BI (Power BI)
