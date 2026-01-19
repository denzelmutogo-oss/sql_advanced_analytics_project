# sql_advanced_analytics_project

---

## 📌 Project Overview

This project is a **continuation of the SQL Exploratory Data Analysis (EDA)** work and moves deeper into **advanced analytical techniques used in real-world Business Intelligence environments**.

While the exploratory phase focused on understanding data structure, coverage, and basic metrics, this project applies **advanced SQL analytics** to answer **how performance changes over time, how metrics accumulate, how different segments contribute to results, and where business performance is strong or weak**.

The analysis is built on **Gold-layer dimensional tables**, ensuring that insights are consistent, trusted, and ready for executive reporting or BI dashboards.

---

## 🧠 Analytical Focus Areas

This project covers advanced analytics patterns commonly required by business stakeholders:

* **Change Over Time Analysis**
  Track trends, growth, and declines across time periods to understand business momentum.

* **Cumulative Analysis**
  Calculate running totals and cumulative metrics to measure progress toward targets and long-term performance.

* **Performance Analysis**
  Evaluate customers, products, or other entities to identify top performers and underperformers.

* **Part-to-Whole Analysis**
  Understand contribution percentages to determine what drives overall results.

* **Data Segmentation**
  Group and compare data across meaningful business segments for deeper insight.

* **Business Reporting Enablement**
  Produce analytics-ready outputs designed for Tableau, Power BI, and executive dashboards.

---

## 🗄️ Data Model Used

All analysis is performed on **analytics-ready Gold tables**:

* **gold.dim_customers** – Customer attributes for segmentation and performance analysis
* **gold.dim_products** – Product hierarchies used for contribution and ranking analysis
* **gold.fact_sales** – Core transactional measures supporting time-based and cumulative metrics

Using dimensional models ensures metrics remain **consistent, explainable, and reusable** across reports.

---

## 📂 Repository Structure

```text
advanced-sql-analytics/
│
├── datasets/               # Reference to Gold-layer analytical tables
│   ├── gold.dim_customers
│   ├── gold.dim_products
│   └── gold.fact_sales
│
├── scripts/                # Advanced analytics SQL scripts
│   ├── change_over_time.sql
│   ├── cumulative_analysis.sql
│   ├── performance_analysis.sql
│   ├── part_to_whole_analysis.sql
│   ├── segmentation_analysis.sql
│   └── reporting_queries.sql
│
├── LICENSE                 # MIT License
└── README.md               # Project documentation
```

The structure reflects **how advanced analytics is organized in production BI teams**, making the project easy to extend and maintain.

---

## 🔍 Analysis Breakdown

### 1️⃣ Change Over Time Analysis

* Compares metrics across days, months, or years
* Identifies trends, seasonality, and growth patterns
* Supports executive-level trend reporting

---

### 2️⃣ Cumulative Analysis

* Calculates running totals and rolling metrics
* Tracks progress toward goals and long-term performance
* Commonly used in financial and operational reporting

---

### 3️⃣ Performance Analysis

* Ranks customers, products, or segments using window functions
* Highlights top contributors and performance gaps
* Supports prioritization and optimization decisions

---

### 4️⃣ Part-to-Whole Analysis

* Calculates percentage contribution to totals
* Identifies key drivers behind overall performance
* Used heavily in executive summaries and dashboards

---

### 5️⃣ Data Segmentation

* Segments data by customer type, product category, or other dimensions
* Enables comparative analysis across business groups
* Supports targeted decision-making

---

### 6️⃣ Reporting-Oriented Queries

* Produces clean, aggregated outputs
* Optimized for Tableau and Power BI consumption
* Reduces downstream calculation complexity in BI tools

---

## 🛠️ SQL Techniques Used

* Window functions (`SUM() OVER`, `RANK()`, `ROW_NUMBER()`)
* Time-based calculations and date logic
* Aggregations and grouping strategies
* Part-to-whole percentage calculations
* Analytical query optimization patterns

---

## 🎯 Business Value

This project demonstrates how advanced SQL analytics:

* Turns trusted data into **actionable insights**
* Enables trend-based and performance-driven decisions
* Reduces BI-layer complexity by handling logic in SQL
* Supports consistent KPI reporting across teams

It highlights not just SQL expertise, but the ability to **think analytically and answer business questions at scale**.

---

## 👤 About Me

**Denzel Mutogo**
*Tableau Developer | Data Analyst | Business Intelligence*

I specialize in building **business-aligned analytics and BI solutions** using SQL, Tableau, and Power BI. My work focuses on turning complex datasets into **clear insights that support confident decision-making**, particularly within healthcare and finance environments.

---

📄 **License:** MIT
