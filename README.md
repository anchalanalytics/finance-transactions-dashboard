# finance-transactions-dashboard
# Finance Transactions Dashboard (Power BI)

An interactive 2-page Power BI dashboard analyzing 50,000+ financial transactions, built to practice real-world data modeling, DAX, and business analysis.

## 📊 Overview

This project takes raw customer and transaction data and turns it into a business-ready dashboard covering revenue trends, transaction behavior, and customer segmentation — the kind of reporting a finance or operations team would actually use.

## 🗂️ Dataset

- **customers.csv** — ~5,000 customer records (demographics, segment, income, occupation)
- **finance_transactions.csv** — ~50,000 transaction records (amount, fees, tax, channel, merchant category, fraud flag, risk score)

## 🛠️ Tools & Skills Used

- **Power BI** — data modeling, report design
- **Power Query** — data cleaning (deduplication, null handling, text standardization)
- **DAX** — time-intelligence measures, dynamic metric selection using field parameters

## ✨ Dashboard Features

- **Overview page:** Key KPIs (Total Amount, Transactions, Avg Transaction Value, Fees, Tax) with Year-over-Year comparisons
- **Transactions page:** Detailed transaction-level breakdown and filtering
- **Dynamic KPI selector** — toggle between metrics using a single visual (built with field parameters)
- **Custom date table** for accurate time-intelligence calculations
- **Segmentation** by customer segment, state, and occupation
- **Slicers** for year, merchant category, and transaction status

## 📁 Files in this Repo

| File | Description |
|---|---|
| `financial analysis.pbix` | Main Power BI dashboard file |
| `customers.csv` | Raw customer data |
| `finance_transactions.csv` | Raw transaction data |
| `Business Requirements.pdf` | Project scope and requirements document |

## 🖼️ Screenshots

**Overview Page**
![Overview Page](Screenshot%202026-09-14%20134824.png)

**Transactions Page**
![Transactions Page](Screenshot%202026-09-14%20134842.png)

*(If the pages are swapped, just switch the two file names above.)*

## 🔍 Key Insight

The dataset includes fraud (`is_fraud`) and risk (`risk_score`) fields, used to analyze which merchant categories carry the highest fraud rates — an angle not always covered in typical BI portfolio projects.

## 🚀 About This Project

Built as part of my data analytics portfolio while preparing for MIS Analyst / Data Analyst roles. Feedback is welcome!

---
**Author:** Anchal
