# 📊 Power BI Sales Dashboard

### 🔗 [My LinkedIn](https://www.linkedin.com/in/abdulrahman-ahmed66)
### 📥 [Download the PBIX File](Project1.pbix?raw=true)
### 🌐 [View Interactive Dashboard](https://your-dashboard-link.com)

<br>

## 🎥 Project Demo  
<img src="Project Description/Project1 Gif.gif?raw=true" width="1000">

<div align="center">
  <img src="Project Description/Screenshot (44).png?raw=true" alt="Dashboard Banner" width="1000" height="500">
</div>

---

## 📝 Introduction

<details> <summary><strong>📌 Overview (click to expand)</strong></summary>
Overview
This Power BI project delivers a comprehensive analysis of sales performance and order management for a retail or distribution business. By transforming raw transactional data into an interactive data model, it enables stakeholders to track key financial metrics, analyze trends over time, and evaluate performance across product categories and geographic territories.
The dashboard is designed to empower data-driven decision-making for sales strategy, inventory planning, and market expansion.

</details> <details> <summary><strong>📂 Data Sources & Model (click to expand)</strong></summary>
Data Sources & Model
The analysis is built on a structured Star Schema data model in Power BI, consisting of fact and dimension tables imported and refined using Power Query.

▼ 📊 Fact Table

fct_Sales: The central fact table containing transactional data.

Key Columns: Commercial, Dealer, Freight, Luxurtail, Production, Maintenance, Displacement, Branch, Issues, and other financial measures.

▼ 📐 Dimension Tables

dim_Date: Contains date hierarchies for time intelligence analysis (Year, Quarter, Month, Day).

dim_Product: Contains product details and hierarchy (Product, Category, Subcategory).

dim_Territory: Defines the sales regions and groups (e.g., Europe, North America, Pacific).

dim_Status: Tracks the status of orders (e.g., Approved, Shipped).

dim_Ship_Method: Specifies the shipping methods used.

▼ ⚙️ Other Components

Measures: Custom DAX calculations (e.g., Total Revenue, Total Due, YTD calculations) are stored in a hidden "Measures" table.

Calculation Groups: Used for dynamic time intelligence comparisons (e.g., Previous Year, MTD, QTD).

</details>

---

## 🎯 Case Study

<details> <summary><strong>📌 Project Overview (click to expand)</strong></summary>
Project Overview
This project transformed sales data into an interactive Power BI dashboard to track order and revenue performance across:

• Geographic territories (Europe, North America, Pacific)

• Product categories (Bikes, Components, Clothing, Accessories)

• Order statuses and financial metrics (Revenue, Tax, Freight)

</details> <details> <summary><strong>📊 Key Results (click to expand)</strong></summary>

  
• $30.09M Total Revenue from 1,465 orders
  
• Bikes dominated as the top category (1,188 orders)

• Europe led as the highest-performing market

• $915.97K Total Freight cost

• $33.93M Total Due (financial obligations)

</details>

---

## 📊 Main KPIs

• 💰 Total Revenue: $30.09M

• 💰 Total Due (Financial Obligation): $33.93M

• 📦 Total Freight: $915.97K

• 📦 Number of Orders: 1,465

• 🏆 Best Performing Product Category: Bikes (1,188 orders)

• 📉 Lower Performing Product Category: Accessories (503 orders)

• 📍 Top Performing Region: Europe

• 🕒 Time-Based Trends: Tracks order volume and revenue by month (2013-2014)

• 📊 Order Status Segmentation: Provides breakdown of orders by status for operational insight

---

## ⚙️ Process

Imported raw data into Power BI

Cleaned and transformed data using Power Query

Built a star schema for modeling relationships

Created DAX measures for dynamic metrics and KPIs

Designed interactive visuals, slicers, and filters

---

## 📐 Data Model  
![Data Model](Project%20Description/Screenshot%20(47).png?raw=true)

---

## 📈 Dashboard Preview  
<img src="Project Description/Screenshot (44).png?raw=true" width="1000">
<img src="Project Description/Screenshot (45).png?raw=true" width="1000">



---

## 🔍 Key Insights

Insight #1: Bikes category dominates revenue - Generating 1,188 orders (81% of total), indicating heavy reliance on a single product category

Insight #2: European market leads performance - Europe outperforms other regions (North America, Pacific) in both order volume and revenue generation

Insight #3: Significant freight costs - $915.97K in freight expenses, representing approximately 3% of total revenue, impacting overall profitability

Insight #4: Seasonal patterns evident - Monthly trends across 2013-2014 show clear fluctuations in order volume and revenue, indicating seasonal demand variations

Insight #5: Revenue-conversion gap - $3.84M difference between Total Due ($33.93M) and Total Revenue ($30.09M), suggesting potential collection or discounting challenges  

---

## 💡 Conclusion

• Identifying revenue concentration in the Bikes category (81% of orders)
• Revealing geographic strengths with Europe as the dominant market
• Highlighting cost optimization opportunities through freight expense analysis
• Tracking seasonal patterns for better inventory and resource planning
• Pinpointing revenue leakage through the $3.84M Total Due vs Revenue gap

---

## 🧰 Tools Used
- **Power BI Desktop**  
- **Power Query**  
- **DAX**  
- **Excel (for data prep)**  
