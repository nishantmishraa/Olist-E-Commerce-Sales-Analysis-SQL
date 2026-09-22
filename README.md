# 🛒 Olist E-Commerce Sales Analysis

An end-to-end **e-commerce business analytics project** built using the Brazilian Olist E-Commerce dataset. I used **SQL to analyze sales, customers, products, sellers, payments, and delivery performance**, and **Power BI to visualize key business metrics and insights**.

The project focuses on answering practical business questions that an e-commerce company could use to understand its customers, revenue, sellers, and operations.

---

## 🎯 Business Questions

The analysis focuses on questions such as:

* Which product categories generate the most revenue?
* Which customers are the most valuable?
* How do sales change over time?
* Where are delivery delays occurring?
* Which sellers are performing well or poorly?
* Which customers are likely to be retained?
* What factors are associated with cancellations and delayed orders?

---

## 📊 Analysis Performed

### Revenue & Product Analysis

* Analyzed revenue by product category and time period.
* Performed Pareto analysis to identify categories contributing the majority of revenue.
* Compared product and category performance.

### Customer Analysis

* Performed **RFM (Recency, Frequency, Monetary) segmentation**.
* Identified high-value customer segments.
* Analyzed customer purchasing and retention patterns.
* Performed cohort analysis to understand customer retention over time.

### Delivery & Operations Analysis

* Analyzed order delivery times and delays.
* Compared delivery performance across locations.
* Investigated patterns in delayed and cancelled orders.

### Seller Performance

* Compared sellers using revenue, orders, ratings, and cancellation metrics.
* Ranked sellers using SQL window functions.
* Identified underperforming seller segments.

---

## 🧠 SQL Techniques Used

* CTEs
* Window Functions
* Multi-table JOINs
* Subqueries
* CASE statements
* Aggregations and GROUP BY
* Date and time functions
* RANK, DENSE_RANK, LAG, LEAD, ROW_NUMBER
* Stored Procedures
* Indexing

---

## 📈 Power BI Dashboard

The SQL analysis was used to build an interactive Power BI dashboard covering:

* Revenue and order KPIs
* Sales trends
* Product category performance
* Customer segmentation
* Seller performance
* Delivery analysis
* Interactive filters and drill-through analysis

**Power BI:** Star Schema, DAX, KPI Cards, Slicers, Drill-through

---

## 📁 Project Structure

```text
Olist-E-Commerce-Sales-Analysis-SQL/
│
├── sql/
│   ├── 01_schema_setup.sql
│   ├── 02_data_exploration.sql
│   ├── 03_revenue_analysis.sql
│   ├── 04_customer_rfm.sql
│   ├── 05_delivery_analysis.sql
│   ├── 06_seller_performance.sql
│   ├── 07_cohort_analysis.sql
│   └── 08_stored_procedures.sql
│
├── data/
│   └── README.md
│
├── powerbi/
│   └── README.md
│
└── README.md
```

---

## 🗄️ Dataset

**Olist Brazilian E-Commerce Public Dataset**

* 100,000+ orders
* 9 related tables
* Data from 2016–2018
* Customer, order, product, seller, payment, review, and delivery information

The dataset was originally published by **Olist** and is available through Kaggle.

---

## 🛠️ Tech Stack

| Tool                          | Purpose                                      |
| ----------------------------- | -------------------------------------------- |
| **MySQL / PostgreSQL**        | Data analysis and business queries           |
| **Power BI**                  | Dashboard and visualization                  |
| **Python / Pandas**           | Data loading and supporting data preparation |
| **MySQL Workbench / DBeaver** | SQL development                              |

---

## 🚀 How to Run

### 1. Get the Dataset

Download the Olist Brazilian E-Commerce dataset and place the CSV files in the `data/` directory.

### 2. Set Up the Database

Run:

```sql
01_schema_setup.sql
```

to create the required database tables.

### 3. Load the Data

Load the Olist CSV files into the corresponding tables using MySQL or another supported SQL environment.

### 4. Run the Analysis

Run the SQL scripts in order:

```text
02 → 03 → 04 → 05 → 06 → 07 → 08
```

The queries progressively cover data exploration, revenue analysis, customer segmentation, delivery performance, seller analysis, cohort analysis, and reusable KPI procedures.

---

## 💡 Key Takeaways

This project helped me practice taking a **raw relational dataset and turning it into business-focused analysis**.

The main workflow was:

**Raw Data → Database → SQL Analysis → Business Insights → Power BI Dashboard**

The project demonstrates my ability to work with relational data, write analytical SQL queries, build reusable datasets, and communicate findings through interactive dashboards.
