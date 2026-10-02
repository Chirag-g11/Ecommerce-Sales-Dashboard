# 📊 E-Commerce Sales & Customer Insights Dashboard

An end-to-end data analytics project that processes, cleans, queries, and visualizes retail e-commerce data to uncover business growth drivers, regional performance metrics, and top-performing product lines.

---

## 🚀 Project Overview
This project simulates a complete data analytics pipeline for a retail e-commerce business. The primary objective is to analyze historical sales transactions to answer critical business questions:
* Which regions and product categories generate the highest revenue and profit?
* What are the monthly sales trends over the years?
* Which sub-categories require strategic inventory attention?

---

## 🛠️ Tech Stack & Tools Used
* **Python (Pandas, NumPy):** Data cleaning, missing value checks, and feature engineering.
* **SQLite & SQL:** Creating relational database tables and extracting business insights via aggregate queries.
* **Power BI:** Building interactive executive dashboard visualizations and KPI cards.
* **Git & GitHub:** Version control and project documentation.

---

## 📈 Dashboard Preview
<img width="1325" height="740" alt="Sales Insights dashboard" src="https://github.com/user-attachments/assets/753e1ef8-9a5f-4e5a-931d-501b338788bd" />


---

## 📂 Project Structure
```text
ecommerce-sales-dashboard/
│
├── datasets/
│   └── Cleaned_Superstore_Data.csv
│
├── notebooks/
│   └── data_cleaning_and_sql_analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── ecommerce_sales_dashboard.pbix
│
└── README.md
```
⚙️ Project Workflow & Steps
1. Data Cleaning & Preprocessing (Python)
Handled duplicate entries and checked for null values using Pandas.

Converted date columns into proper datetime formats.

Feature Engineering: Added derived columns such as Order_Year, Order_Month, and Profit_Margin to streamline time-series and profitability analysis.

2. Data Extraction & Analysis (SQL)
Loaded the cleaned DataFrame into an SQLite database (ecommerce_project.db) and wrote analytical queries to extract key metrics:

Regional Sales & Profit Analysis: Grouped data by region to calculate total revenue and profit distributions.

Product Performance: Ranked top-selling products by total sales and quantity.

Monthly Time-Series Trends: Evaluated revenue growth month-over-month.

3. Interactive Visualization (Power BI)
Designed an executive-level dashboard featuring:

KPI Cards: Total Revenue, Total Profit, Total Orders, and Average Profit Margin.

Line Chart: Monthly Revenue Trend over time.

Donut Chart: Sales distribution across product categories (Technology, Furniture, Office Supplies).

Bar Charts: Breakdown of regional performance and top sub-categories.

Slicers: Interactive year filters to drill down into specific timeline data.

📊 Key Business Insights
Top Revenue Region: The West region generated the highest overall revenue, followed closely by the East region.

Category Dominance: Technology emerged as the leading product category by sales value.

Seasonal Spikes: Sales experience a sharp upward trend toward the final quarter of the year, indicating heavy seasonal demand.

👤 Author
Chirag Goyal

Connect with me on [GitHub](https://github.com/chirag-g11) | [LinkedIn](www.linkedin.com/in/chirag-goyal-a7715a289)
