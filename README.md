# 🧪 PySpark SQL Without Temp Views – Bronze to Silver Example

This repository contains a simple and production-like example of how to use PySpark's `spark.sql()` function by passing DataFrames directly as named parameters — avoiding the need for temporary views.

## 📖 Related Article

Check out the full Medium article here:  
👉 [Efficient Spark SQL without Temp Views: Cleaner Data Pipelines](https://medium.com/@tugnolialessio)

> ✅ Works with PySpark 3.3 and later

## 📌 What You'll Learn

- How to write SQL queries on DataFrames without creating temp views
- How to build a simple data transformation pipeline (Bronze → Silver layer)
- Why this approach improves clarity and maintainability in Spark projects

## 🛠️ Example Overview

We simulate a medallion architecture scenario with:
- **Bronze Layer**: Raw data for customers and orders
- **Silver Layer**: 
  - Join customers and orders
  - Filter high-value orders
  - Aggregate spending per customer
