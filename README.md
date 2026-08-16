# Zepto E-Commerce Inventory Data Analysis

A complete **Data Analyst portfolio project** demonstrating end-to-end SQL data analysis of **Zepto e-commerce inventory data** using **PostgreSQL**.

The project focuses on data cleaning, exploratory analysis, business insights, and SQL-based reporting to understand product pricing, discounts, inventory, stock availability, and category-level performance.

## 📌 Overview

This project analyzes Zepto's e-commerce inventory dataset to answer practical business questions such as:

* Which product categories generate the most revenue potential?
* Which products have the highest discounts?
* What products are out of stock?
* How does product pricing vary across categories?
* Which products contribute the most to inventory value?
* What insights can help improve inventory and pricing decisions?

The project is designed to showcase practical **SQL, data analysis, and business intelligence skills** relevant to a Data Analyst role.

## 📊 Dataset

The dataset contains product-level information from Zepto's e-commerce inventory, including fields such as:

* Product name
* Category
* Selling price
* MRP
* Discount percentage
* Available quantity
* Stock status
* Product weight
* Product value

The data is loaded into **PostgreSQL** for cleaning, transformation, and analysis.

## 🛠️ Tools & Technologies

* **PostgreSQL** — Data storage and SQL analysis
* **SQL** — Data cleaning, transformation, aggregation, and business analysis
* **Excel / CSV** — Dataset preparation and inspection
* **Power BI / Tableau** — Dashboard and data visualization
* **GitHub** — Project documentation and portfolio presentation

## 🔄 Project Steps

### 1. Data Collection

Imported the Zepto inventory dataset into PostgreSQL.

### 2. Data Cleaning

Performed data quality checks and handled issues such as:

* Missing values
* Duplicate records
* Incorrect data types
* Invalid pricing values
* Inconsistent category or stock information

### 3. Data Exploration

Used SQL queries to explore:

* Product and category distribution
* Pricing patterns
* Discount percentages
* Inventory levels
* Stock availability

### 4. SQL Analysis

Created queries using:

* `SELECT`, `WHERE`, `GROUP BY`, and `ORDER BY`
* Aggregate functions such as `SUM`, `AVG`, `COUNT`, and `MAX`
* `CASE` statements
* Common Table Expressions (CTEs)
* Window functions
* Subqueries

### 5. Business Insights

Converted SQL findings into actionable insights related to:

* Inventory management
* Product pricing
* Discount strategy
* Product availability
* Category performance

### 6. Dashboard

Built an interactive dashboard to present the key findings in an easy-to-understand format.

Suggested dashboard metrics include:

* Total Products
* Total Inventory Value
* Average Selling Price
* Average Discount %
* In-Stock vs Out-of-Stock Products
* Category-wise Inventory
* Top Products by Revenue Potential
* Highest Discounted Products

## 📈 Dashboard

The dashboard provides a visual summary of the analysis and allows users to explore inventory and product-level performance.

**Key dashboard sections:**

1. **Overview KPIs**
2. **Category Performance**
3. **Pricing & Discounts**
4. **Stock Availability**
5. **Top Products**
6. **Inventory Value Analysis**

> Add your dashboard screenshot or Power BI/Tableau link here.

## 🔍 Key Results

The analysis provides insights into:

* Products and categories with the highest inventory value
* Products receiving the largest discounts
* Categories with stronger pricing and inventory performance
* Products that are frequently unavailable
* Differences between MRP and actual selling prices
* Inventory concentration across product categories

These insights demonstrate how SQL analysis can support **data-driven pricing, inventory, and business decisions**.

## ▶️ How to Run

### Prerequisites

Install or have access to:

* PostgreSQL
* pgAdmin or another SQL client
* Power BI / Tableau (optional, for the dashboard)

### Setup

1. Clone or download this repository.
2. Create a PostgreSQL database.
3. Import the Zepto dataset into the database.
4. Run the SQL scripts in the recommended order:

   * Data Import
   * Data Cleaning
   * Exploratory Analysis
   * Business Analysis
5. Open the dashboard file in Power BI/Tableau if included.
6. Connect the dashboard to the analyzed dataset and refresh the data.

## 📁 Project Structure

```text
Zepto-Data-Analysis/
│
├── dataset/
│   └── zepto_inventory.csv
│
├── sql/
│   ├── data_cleaning.sql
│   ├── exploratory_analysis.sql
│   └── business_analysis.sql
│
├── dashboard/
│   └── zepto_dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

## 💡 Skills Demonstrated

* SQL & PostgreSQL
* Data Cleaning
* Exploratory Data Analysis
* Business Analysis
* Data Visualization
* Dashboard Development
* Data Storytelling
* Translating business questions into SQL queries

## 👤 About the Project

This project is part of my **Data Analyst Portfolio** and demonstrates my ability to work with a real-world-style e-commerce dataset, perform end-to-end SQL analysis, and communicate business insights through dashboards.

**Author:** Your Name
**Role:** Aspiring Data Analyst
**Tools:** PostgreSQL | SQL | Power BI/Tableau | Excel
