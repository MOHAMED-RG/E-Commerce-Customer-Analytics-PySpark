# 🛒 E-Commerce Customer Analytics with PySpark

## 📌 Project Overview

This project analyzes e-commerce customer data using **PySpark on Databricks**.

The goal is to explore customer segments, demographics, geographic distribution, and customer acquisition costs while practicing core Spark data-processing and analytics concepts.

The project covers the workflow from **data inspection and transformation to customer analysis, Spark SQL, Delta Lake storage, partitioning, and visualization**.

## 📊 Dataset

The project uses the **E-Commerce Sales Analytics Dataset** from Kaggle.

**Dataset:** [E-Commerce Sales Analytics Dataset](https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics/data)

## 🛠️ Technologies

* Python
* PySpark
* Apache Spark
* Databricks
* Spark SQL
* Delta Lake
* Matplotlib

## 🔄 Project Workflow

1. Load the dataset into Databricks
2. Inspect the schema and data quality
3. Check for duplicates and missing values
4. Create age groups and acquisition cost categories
5. Perform customer analysis using PySpark
6. Apply aggregations and window functions
7. Perform analysis using Spark SQL
8. Store the processed data as a Delta table
9. Partition the data by `region`
10. Visualize key analytical results
11. Summarize the main findings

## 🔍 Customer Analysis

The analysis includes:

* Customer segment distribution
* Gender distribution
* Age groups
* Average age by customer segment
* Average acquisition cost by customer segment
* Customer distribution by region
* Average acquisition cost by region
* Customer distribution by city
* Customer distribution by state
* Customer distribution by country
* Acquisition cost categories
* Customer ranking by acquisition cost
* Customer segment and gender distribution

## ⚡ Spark Concepts

The project provides practical experience with:

* DataFrames
* Schema and data types
* `select()`
* `filter()`
* `withColumn()`
* `groupBy()`
* Aggregations
* `orderBy()`
* Window functions
* Temporary views
* Spark SQL
* Delta tables
* Partitioning

## 💾 Data Storage

The final customer analysis DataFrame was stored as a **Delta table** in Databricks.

The data was partitioned by **`region`**, and the partitioned table was queried using a specific region to demonstrate partition-based filtering.

## 📈 Visualizations

### Customer Count by Segment

![Customer Count by Segment](customer_count_by_segment.png)

### Gender Distribution

![Gender Distribution](gender_distribution.png)

### Customer Distribution by Region

![Customer Distribution by Region](customer_distribution_by_region.png)

### Average Acquisition Cost by Customer Segment

![Average Acquisition Cost by Customer Segment](average_acquisition_cost_by_segment.png)

## 🔑 Key Findings

* The **Consumer** segment has the largest customer base with **13,638 customers**.
* The **Premium** segment has **6,301 customers**, followed by **VIP with 2,542** and **Business with 2,519**.
* The dataset contains **14,925 customers from the USA**.
* Among USA customers, there are **7,191 Female**, **7,150 Male**, and **584 Non-Binary** customers.
* The **Business** segment has the highest average customer age at approximately **46.63 years**.
* Among customers with acquisition costs above 50, the **Business** segment has the highest average acquisition cost at approximately **65.42**.
* The final customer analysis data was stored as a **Delta table** and partitioned by **`region`**.

## 📁 Project Files

```text
E-Commerce-Customer-Analytics-PySpark/
│
├── ecommerce_customer_analytics.ipynb
├── README.md
├── customer_count_by_segment.png
├── gender_distribution.png
├── customer_distribution_by_region.png
└── average_acquisition_cost_by_segment.png
```
