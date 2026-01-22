# Advanced SQL Analytics Project

---

## 📌 Project Overview

This project focuses **specifically on advanced SQL analytics**, building on a separate EDA phase. The goal here is to answer **business questions around trends, performance, and contribution** using reporting-ready SQL, similar to how analytics is handled in real BI environments.

The queries are designed to sit **behind Tableau and Power BI dashboards**, providing consistent metrics and reducing the need for complex calculations in the BI layer.

All analysis is performed on **Gold-layer dimensional tables**, ensuring results are trusted and reusable.

---

## 🎯 Business Questions Addressed

This project helps answer questions such as:

* How is performance changing over time?
* What do cumulative results look like within a period?
* Which customers or products are driving the majority of results?
* How much does each segment contribute to the total?
* How do different segments compare to each other?

These are common questions from leadership and stakeholders once basic reporting is already in place.

---

## 🛠️ Analytical Approach

Instead of handling logic in dashboards or spreadsheets, this project uses **advanced SQL patterns** to:

* Centralize KPI logic
* Support trend, ranking, and cumulative analysis
* Produce clean, aggregated outputs for BI tools

This keeps dashboards simpler and ensures the same question always returns the same answer.

---

## 🗄️ Data Model Used

Analysis is built on analytics-ready dimensional tables:

* **gold.dim_customers** – segmentation and customer analysis
* **gold.dim_products** – product hierarchy and contribution analysis
* **gold.fact_sales** – core measures for time-based and cumulative metrics

---

## 📂 Repository Structure

```text
advanced-sql-analytics/
│
├── scripts/
│   ├── change_over_time.sql
│   ├── cumulative_analysis.sql
│   ├── performance_analysis.sql
│   ├── part_to_whole_analysis.sql
│   ├── segmentation_analysis.sql
│   └── reporting_queries.sql
│
├── LICENSE
└── README.md
```

---

## 🔍 Analytics Covered

* Change over time analysis
* Cumulative and running totals
* Performance ranking using window functions
* Part-to-whole contribution analysis
* Segment-based comparisons

---

## 📊 Business Impact

In a BI setting, this type of analysis:

* Makes trends and performance gaps visible
* Reduces repeated KPI logic across dashboards
* Improves confidence in reported numbers
* Speeds up responses to ad-hoc business questions

---

## 👤 About Me

**Denzel Mutogo**
Tableau Developer | Data Analyst | Business Intelligence

---

📄 **License:** MIT
