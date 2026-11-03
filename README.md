# Cafe Sales Data Pipeline

An end-to-end data analytics project featuring data cleaning, cross-imputation logic, anomaly handling, and exploratory data visualization using Python (Pandas, Seaborn, Matplotlib).

## 📊 Project Overview

This project processes raw e-commerce transaction logs to prepare a clean, analysis-ready dataset. It handles messy data types, resolves missing values through mathematical dependency logic (`Total Spent = Quantity * Price Per Unit`), and visualizes core business metrics.

## 🛠️ Tech Stack & Libraries

- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Visual Studio Code

## 🧹 Key Data Cleaning & Imputation Steps

1. **String & Regex Normalization:** Standardized complex revenue strings and location categories.
2. **Cross-Imputation:** Imputed missing values dynamically using inter-column relationships (`Quantity`, `Price Per Unit`, `Total Spent`).
3. **Deterministic Mapping:** Resolved missing item names based on unique price per unit mappings.
4. **Data Validation:** Dropped unresolved anomalies and standardized data types for analytics readiness.

## 📈 Dashboard Visualizations

The analysis generates a 4-panel professional dashboard featuring:

- **Daily Sales Revenue Trend Over Time** (Line Chart)
- **Top-Selling Products by Total Quantity** (Horizontal Bar Chart)
- **Total Revenue by Location / Order Type** (Bar Chart)
- **Payment Method Proportion Share** (Donut Chart)

---

_Created as part of Siddiq Makhalli's Data Analytics Portfolio._
