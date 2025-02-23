<img width="113" alt="blinkit i" src="https://github.com/user-attachments/assets/a98a3134-261e-412b-aad1-3dfdaf48eaf1" />

# Blinkit Sales Analysis Project

## 📊 Project Overview
The **Blinkit Sales Analysis** project aims to uncover key business insights from sales data using **MySQL Workbench** for data extraction and transformation, and **Power BI** for dynamic visualization and reporting. The objective is to analyze sales trends, item characteristics, outlet performance, and customer preferences to support data-driven decision-making.

---

## 🛠️ Tools & Technologies
- **Database Management:** MySQL Workbench 8.0
- **Data Visualization:** Power BI
- **Query Language:** SQL (Structured Query Language)

---

## 🎯 Key Objectives
- Analyze total and average sales.
- Examine item characteristics such as fat content and type.
- Assess outlet performance based on location, size, and establishment year.
- Determine customer preferences through sales and rating patterns.

---

## 📁 Data Analysis Process

### 1. **Data Extraction (MySQL Workbench)**
The data is stored in a single table named `blinkit`, which contains sales, product, and outlet information. SQL queries were used to extract the following insights:

#### 🔑 **Key Performance Indicators (KPIs):**
- **Total Sales (in millions):** Aggregated total sales across all outlets.
- **Average Sales per Item:** Average sales value per item.
- **Total Number of Items:** Total count of items sold.
- **Average Rating:** Mean customer rating across all items.

#### 🏷️ **Sales Analysis Dimensions:**
- **Sales by Fat Content:** Total and average sales based on item fat content.
- **Sales by Item Type:** Analysis of sales performance by item category.
- **Sales by Outlet Location:** Geographical impact on sales performance.
- **Sales by Establishment Year:** Performance trends based on outlet age.
- **Sales by Outlet Size:** Sales contribution by outlet size with percentage breakdown.
- **Fat Content Analysis by Outlet Location:** Relationship between item fat content and outlet location.
- **Comprehensive Outlet Analysis:** All key metrics (sales, ratings, item count) analyzed by outlet type.

---

### 2. **Data Visualization (Power BI)**
Key insights derived from SQL analysis were visualized in Power BI using:
- **Interactive Dashboards:** To explore KPIs and trends dynamically.
- **Bar & Pie Charts:** To compare sales by item type, fat content, and outlet location.
- **Line Graphs:** For temporal analysis of sales by establishment year.
- **Heatmaps:** Highlighting relationships between outlet size, location, and sales.

---

## 📌 Key Insights & Findings
- **Item Fat Content:** Low-fat items contributed the highest sales volume.
- **Top-Performing Item Types:** Processed foods and beverages led total sales.
- **Outlet Location Trends:** Urban areas generated higher sales compared to suburban and rural areas.
- **Outlet Size Impact:** Medium-sized outlets contributed the majority of sales revenue.
- **Outlet Establishment Year:** Newly established outlets (post-2010) showed faster sales growth.

---

## 💡 Conclusion
The **Blinkit Sales Analysis** reveals that product characteristics and outlet demographics significantly influence sales performance. The insights generated from this project can guide:
- Inventory optimization based on popular item types.
- Strategic expansion focusing on urban markets.
- Customized marketing strategies for low-performing outlet types.

---

## 🚀 How to Reproduce This Project

### Prerequisites:
- MySQL Workbench 8.0+
- Power BI Desktop

### Steps:
1. **Database Setup:**
   - Import the sales dataset into MySQL Workbench.
2. **Run SQL Queries:**
   - Execute the provided SQL scripts to generate KPIs and detailed sales reports.
3. **Power BI Integration:**
   - Connect Power BI to MySQL database.
   - Use SQL outputs to create visualizations and dashboards.

---

## 🔗 SQL Queries Reference
The complete SQL queries used in this analysis are included in the `/SQL_Query.sql` file.

---

## 📃 License
This project is licensed under the [MIT License](LICENSE).

---
