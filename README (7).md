# Olist E-Commerce Analytics Dashboard

End-to-end data analytics project analyzing 99K+ e-commerce transactions from the Olist Brazilian E-Commerce dataset — covering data cleaning, exploratory data analysis, SQL-based querying, RFM customer segmentation, and an interactive Power BI dashboard.

## 📊 Project Overview

This project turns raw, messy multi-table e-commerce data into actionable business insights — identifying revenue trends, top-performing product categories, and at-risk customer segments to support data-driven retention strategy.

**Dataset:** [Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle)

## 🔑 Key Insights

- Analyzed **99K+ transactions** totaling **20M+ in revenue**
- Performed **RFM (Recency, Frequency, Monetary) segmentation**, revealing:
  - **41% of customers classified as "At Risk"**
  - **34% "Loyal Customers"**
  - **16% "Champions"** (highest-value, most engaged)
  - Remaining segment: **"Churned"**
- Identified top revenue-driving categories: **bed_bath_table, health_beauty, computers_accessories, furniture_decor**
- Average order value: **~173 BRL**

## 🛠️ Tech Stack

- **Data Cleaning & EDA:** Python, Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Database & Querying:** SQLite, SQL
- **Dashboarding:** Power BI
- **Environment:** Google Colab

## 🔄 Workflow

1. **Data Ingestion** – Loaded 9 relational CSV files (orders, customers, payments, products, reviews, sellers, geolocation)
2. **Data Cleaning** – Handled missing values, removed duplicates, converted date fields, standardized product categories
3. **Merging** – Combined all tables into a single analysis-ready master dataset
4. **Exploratory Data Analysis** – Analyzed monthly revenue trends, payment type distribution, and delivery time patterns
5. **RFM Segmentation** – Scored customers on Recency, Frequency, and Monetary value; classified into actionable segments
6. **SQL Layer** – Loaded cleaned data into SQLite; wrote queries for revenue trends, top customers, and segment-wise analysis
7. **Dashboard** – Built an interactive Power BI dashboard with KPI cards, revenue trend, top categories, and customer segment breakdown

## 📁 Repository Contents

- `olist_analysis.ipynb` — Full analysis notebook (cleaning, EDA, RFM, SQL queries)
- `dashboard_screenshot.png` — Power BI dashboard preview
- `README.md` — Project documentation

## 📈 Dashboard Preview

*(Add your Power BI dashboard screenshot here)*

## 🚀 How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
2. Open `olist_analysis.ipynb` in Google Colab or Jupyter Notebook
3. Upload the dataset CSVs and run all cells sequentially
4. Exported CSVs (`olist_cleaned_master.csv`, `olist_rfm_segments.csv`) can be loaded into Power BI or Tableau to rebuild the dashboard

---

**Author:** Samarth Gajanan Marathe
[GitHub](https://github.com/samarthx4216) | [LinkedIn](https://linkedin.com/in/samarthmarathe)
