# 🛒 E-Commerce Customer Analytics with PySpark

## 📌 Overview

Customer analytics project built using **PySpark and Databricks**. The project focuses on customer demographics, segments, geographic distribution, and acquisition costs while applying core Spark data-processing concepts.

## 📊 Dataset

**E-Commerce Sales Analytics Dataset** — Kaggle

[Dataset on Kaggle](https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics/data)

## 🛠️ Technologies

* Python
* PySpark
* Apache Spark
* Databricks
* Spark SQL
* Delta Lake
* Matplotlib

## 🔄 Workflow

```text
Load Data
   ↓
Data Inspection
   ↓
Data Transformation
   ↓
Customer Analysis
   ↓
Spark SQL
   ↓
Delta Table
   ↓
Partitioning
   ↓
Visualization
   ↓
Key Findings
```

## 🔍 Analysis

The project analyzes:

* Customer segments
* Gender distribution
* Age groups
* Average age by segment
* Customer distribution by region
* Top cities, states, and countries
* Customer acquisition cost
* Customer ranking by acquisition cost

## ⚡ Spark & Databricks

Core Spark concepts practiced:

* DataFrames
* Schema and data types
* Filtering and selecting
* Aggregations
* Grouping and sorting
* Joins
* Union
* Window functions
* Spark SQL
* Lazy evaluation
* Narrow and wide transformations
* Driver and executors
* `repartition()` and `coalesce()`
* Delta tables
* Partitioning

## 📈 Visualizations

### Customer Count by Segment

![Customer Count by Segment](images/customer_count_by_segment.png)

### Gender Distribution

![Gender Distribution](images/gender_distribution.png)

### Customer Distribution by Region

![Customer Distribution by Region](images/customer_distribution_by_region.png)

### Average Acquisition Cost by Customer Segment

![Average Acquisition Cost by Customer Segment](images/average_acquisition_cost_by_segment.png)

## 🔑 Key Findings

* **Consumer** is the largest customer segment with **13,638 customers**.
* **Premium** has **6,301 customers**, followed by **VIP (2,542)** and **Business (2,519)**.
* The dataset contains **14,925 customers from the USA**.
* USA customers include **7,191 Female**, **7,150 Male**, and **584 Non-Binary** customers.
* **Business** has the highest average customer age at approximately **46.63 years**.
* Among customers with acquisition costs above 50, **Business** has the highest average acquisition cost at approximately **65.42**.
* The final customer analysis data was stored as a **Delta table** and partitioned by **region**.

## 📁 Project Structure

```text
E-Commerce-Customer-Analytics-PySpark/
│
├── ecommerce_customer_analytics.ipynb
├── README.md
│
└── images/
    ├── customer_count_by_segment.png
    ├── gender_distribution.png
    ├── customer_distribution_by_region.png
    └── average_acquisition_cost_by_segment.png
```

## 👤 Author

**Mohamed Abdelmenem**

Aspiring Data Scientist | Python | SQL | Machine Learning | PySpark

[GitHub](https://github.com/MOHAMED-RG)
