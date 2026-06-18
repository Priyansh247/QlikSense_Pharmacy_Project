# 💊 Pharmacy Data Analytics Dashboard
### Built using the DAR Approach — Dashboard → Analytics → Reporting

---

## 📌 Project Overview

This project analyzes real-world pharmacy data to uncover sales trends, revenue patterns, and customer/patient behavior. The entire workflow follows the **DAR (Dashboard → Analytics → Reporting)** approach — starting from an interactive visual layer, drilling into analytical insights, and culminating in structured business reports.

Raw data was extracted, cleaned, and transformed using an **ETL pipeline** before being loaded into **Qlik Sense** for visualization.

---

## 🏗️ DAR Approach

```
D — Dashboard    →   Interactive Qlik Sense views for KPI monitoring
A — Analytics    →   Deep-dive analysis into sales trends & patient behavior  
R — Reporting    →   Structured summary reports for business decision-making
```

---

## ⚙️ ETL Pipeline

```
Raw Excel Data
      ↓
Data Extraction   (Excel → SQL)
      ↓
Data Cleaning     (nulls, duplicates, format standardisation, type casting)
      ↓
Data Transformation (aggregations, joins, derived KPIs)
      ↓
Data Loading      (into Qlik Sense for visualisation)
```

### Cleaning steps performed:
- Removed duplicate records and null entries
- Standardised date formats and product name inconsistencies
- Resolved missing values in revenue and quantity columns
- Normalised customer/patient identifiers across data sources
- Created derived columns (e.g., monthly revenue, product category groupings)

---

## 📊 Dashboard Highlights

### 💰 Sales & Revenue
- Monthly and yearly revenue trends
- Top-selling products by quantity and revenue
- Revenue breakdown by product category
- Sales performance over time (growth/decline tracking)

### 🧑‍⚕️ Customer / Patient Analytics
- Patient visit frequency and retention trends
- Repeat vs. new customer split
- High-value customer segmentation
- Purchase pattern analysis by demographics

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Qlik Sense** | Dashboard & interactive visualisation |
| **SQL** | Data extraction, transformation, querying |
| **Excel** | Raw data source, initial exploration |

---

## 📁 Project Structure

```
pharmacy-analytics/
│
├── data/
│   ├── raw/                  # Original Excel source files
│   └── cleaned/              # Cleaned and transformed data
│
├── sql/
│   └── etl_queries.sql       # All extraction and transformation queries
│
├── dashboard/
│   └── pharmacy_dashboard.qvf   # Qlik Sense app file
│
├── reports/
│   └── summary_report.pdf    # Final business report
│
└── README.md
```

---

## 🔍 Key Insights Uncovered

- Identified the **top 5 revenue-generating products** contributing to over 60% of total sales
- Detected a **seasonal spike in patient visits** during winter months, informing stock planning
- Flagged **3 product categories** with declining sales trends requiring review
- Revealed that **repeat customers** account for ~70% of total revenue

---

## 🎯 Business Value

This project simulates the kind of data monitoring and KPI reporting used in real-world operations — tracking transactional patterns, identifying anomalies, and enabling faster, evidence-based decisions. Skills directly applicable to **fraud analytics, risk monitoring, and compliance reporting** in financial and banking environments.

---

## 🚀 How to Open the Dashboard

1. Install **Qlik Sense Desktop** (free): [Download here](https://www.qlik.com/us/try-qlik/qlik-sense-desktop)
2. Open Qlik Sense Desktop
3. Click **Import** and select `pharmacy_dashboard.qvf`
4. Explore the Dashboard → Analytics → Reporting layers

---

## 👤 Author

**Priyansh Tomar**  
[LinkedIn](https://www.linkedin.com/in/priyansh-tomar-4655911bb/) • [GitHub](https://github.com/Priyansh247)
