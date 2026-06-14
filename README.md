# 📊 Sales Performance Analytics Dashboard

## 📌 Project Overview

This project demonstrates an end-to-end Data Analytics workflow using **Python, MySQL, and Power BI**. The objective was to analyze sales performance, identify key business insights, and build an interactive dashboard for decision-making.

The project starts with raw sales data in Excel format, which is cleaned and transformed using Python, stored in MySQL for analysis, and finally visualized through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* Jupyter Notebook
* MySQL
* Power BI
* Microsoft Excel

---

## 🔄 Project Workflow

```text
Raw Excel Data
      ↓
Data Cleaning (Python)
      ↓
Data Storage (MySQL)
      ↓
Data Analysis (SQL)
      ↓
Dashboard Creation (Power BI)
      ↓
Business Insights
```

---

## 📂 Project Files

```text
Sales-Performance-Analytics/
│
├── sales_raw_data.xlsx
├── clean sales data.ipynb
├── SQL queries.sql
├── Sales_Performance_Dashboard.pbix
├── dashboard_screenshot.png
└── README.md
```

---

## 📈 Dashboard KPIs

* Total Sales
* Total Profit
* Total Orders
* Profit Margin (%)
* Total Cost
* Average Order Value (AOV)

---

## 📊 Dashboard Features

### Interactive Filters

* Year Filter
* Month Filter
* Region Filter

### Visualizations

* Sales by Month
* Profit by Product
* Profit by Region
* Sales by Customer and Product
* Sales by Region

---

## 🧮 DAX Measure Used

### Average Order Value (AOV)

```DAX
AOV =
DIVIDE(
    SUM('sales_data sales_info'[Sales]),
    DISTINCTCOUNT('sales_data sales_info'[Order_ID])
)
```

---

## 🔍 Key Business Insights

* Achieved Total Sales of 16M.
* Generated Total Profit of 4M.
* Maintained a Profit Margin of 25%.
* South Region recorded the highest sales.
* Printer category generated the highest profit.
* Average Order Value (AOV) reached 41.10K.

---

## 🎯 Skills Demonstrated

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* SQL Queries and Database Management
* Data Visualization
* Power BI Dashboard Development
* DAX Calculations
* Business Intelligence Reporting

---

## 🚀 How to Run This Project

### Step 1: Data Cleaning

Open and run:

```bash
clean sales data.ipynb
```

### Step 2: Database Setup

Execute:

```sql
SQL queries.sql
```

### Step 3: Dashboard

Open:

```text
Sales_Performance_Dashboard.pbix
```

using Power BI Desktop.

---

## 👨‍💻 Author

**Aakash Harabak**

Aspiring Data Analyst

### Skills

* SQL
* Python
* Power BI
* Data Analytics
* Data Visualization

📧 Email: [harabakaakash@gmail.com](mailto:harabakaakash@gmail.com)

🔗 GitHub: https://github.com/AakashHarabak
