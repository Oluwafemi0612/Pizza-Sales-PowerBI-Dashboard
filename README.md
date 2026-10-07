# 🍕 Pizza Sales Performance & Operational Analytics Dashboard

## 📊 Project Overview
This project features a comprehensive, multi-page **Power BI Dashboard** built to analyze a pizza restaurant chain's annual sales performance, operational trends, product popularity, and customer behavior. 

The dashboard processes raw transactional data into actionable business intelligence, allowing stakeholders to identify peak operating times, optimize inventory management, and pinpoint top- and bottom-performing menu items to maximize profitability.

---

## 🔗 Live Interactive Dashboard
👉 [Click here to interact with the live dashboard](https://mavenshowcase.com/project/57962)

---

## 📈 Executive Summary (Key Performance Indicators)
The business generated strong operational metrics across the active fiscal period:
* **Total Revenue:** \$817.86K
* **Total Orders:** 21,350 orders
* **Total Pizzas Sold:** 49,574 units
* **Average Order Value:** \$38.31
* **Average Pizzas Per Order:** 2.32

---

## 🔍 Dashboard Architecture & Deep Dive Insights

### 🧭 Page 1: Operational Trends & Sales Performance (Home)
This view focuses on time-based trends and structural distributions of sales across categories and sizes to assist with staffing and operational scheduling.

* **Busiest Operational Windows:** 
  * **Daily Trend:** Order volume heavily peaks at the end of the week, with **Friday** (3,538 orders) and **Saturday** (3,158 orders) representing the highest-traffic days. 
  * **Monthly Trend:** Demand exhibits seasonality, hitting maximum volumes during **July** (1,935 orders) and **January** (1,845 orders).
* **Category Breakdown:** The **Classic** pizza category represents the core business driver, contributing to **26.91%** of sales and leading in total volume (**14,888 units sold**).
* **Size Preferences:** **Large pizzas** heavily dominate consumer preference, accounting for **45.89%** of total sales.

### 📸 Dashboard Visuals

#### Page 1: Operational Trends & Sales Performance (Home)
<img width="1484" height="806" alt="Screenshot 2026-10-06 204555" src="https://github.com/user-attachments/assets/8e57f489-fa29-4e8a-91d8-cd17c769a609" />


#### Page 2: Product Performance Breakdown (Best/Worst Sellers)
<img width="1479" height="811" alt="Screenshot 2026-10-06 204853" src="https://github.com/user-attachments/assets/e6edbcb9-264e-44f7-a9d3-3d4fe4137741" />



### 🏆 Page 2: Product Performance Breakdown (Best/Worst Sellers)
This view provides a highly granular look at product rankings across Revenue, Quantity, and Total Orders to assist culinary teams with menu engineering.

* **🥇 Top Performers (Best Sellers):**
  * **By Revenue:** **The Thai Chicken Pizza** generates the maximum revenue (\$43K).
  * **By Quantity & Orders:** **The Classic Deluxe Pizza** contributes to both maximum total quantities and total orders.
* **💔 Underperformers (Worst Sellers):**
  * **The Brie Carre Pizza** consistently ranks at the absolute bottom across **all metrics** (minimum revenue at \$12K, minimum quantities at 490, and minimum total orders at 480). This identifies it as a prime candidate for a recipe revamp or removal from the menu.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Tool:** Power BI Desktop / Power BI Service (Bootcamp Environment)
* **Data Engineering & ETL:** Power Query (Data cleaning, handling missing values, type standardization)
* **Data Modeling:** Star Schema design containing fact tables and dimension lookups
* **Analytical Calculations:** DAX (Data Analysis Expressions) utilized for building time-intelligence metrics and custom KPIs
* **UI/UX Design:** Formatted using a cohesive corporate color scheme, clear structural margins, visual anchors, and dynamic native page navigation toggles (`Home` vs. `Best/Worst Sellers`).

---

## 📂 Repository Structure
* `Pizza_PowerBI_project.pbix` — Core Power BI binary file housing data models and dashboard visuals.
* `pizza_sales.csv` — Raw sales dataset used for modeling and transparency.
