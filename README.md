# 📊 Power BI Sales Dashboard  

### 🔗 [My LinkedIn](https://www.linkedin.com/in/abdulrahman-ahmed66)  
### 📥 [Download the PBIX File](Project1.pbix?raw=true)  

---

## 🎥 Project Demo  
<img src="Project Description/Project1 Gif.gif?raw=true" width="1000">  

<div align="center">
  <img src="Project Description/Screenshot (44).png?raw=true" alt="Dashboard Banner" width="1000" height="500">
</div>  

---

## 📝 Introduction  

<details>  
<summary><strong>📌 Overview (click to expand)</strong></summary>  

This Power BI project delivers a comprehensive analysis of **sales performance** and **order management** for a retail or distribution business.  

By transforming raw transactional data into an interactive data model, it enables stakeholders to:  
- Track key financial metrics  
- Analyze trends over time  
- Evaluate performance across product categories and geographic territories  

👉 The dashboard empowers **data-driven decision-making** for sales strategy, inventory planning, and market expansion.  

</details>  

<details>  
<summary><strong>📂 Data Sources & Model (click to expand)</strong></summary>  

The analysis is built on a structured **Star Schema** data model in Power BI, consisting of fact and dimension tables imported and refined using **Power Query**.  

---

### 📊 Fact Table  
**fct_Sales** → Central fact table containing transactional data.  

**Key Columns**:  
Commercial, Dealer, Freight, Luxurtail, Production, Maintenance, Displacement, Branch, Issues, and other financial measures.  

---

### 📐 Dimension Tables  
- **dim_Date** → Provides a full date hierarchy (Year, Quarter, Month, Day).  
  - Enables YTD, MTD, seasonal, and trend analysis.  

- **dim_Product** → Product details and hierarchy (Product, Category, Subcategory).  

- **dim_Territory** → Sales regions (Europe, North America, Pacific).  

- **dim_Status** → Tracks order status (Approved, Shipped, etc.).  

- **dim_Ship_Method** → Shipping methods used.  

---

### ⚙️ Other Components  
- **Measures** → Custom DAX calculations (Revenue, Total Due, YTD, etc.).  
- **Calculation Groups** → Enable dynamic time intelligence (Previous Year, MTD, QTD).  

</details>  

---

## 🎯 Case Study  

<details>  
<summary><strong>📌 Project Overview (click to expand)</strong></summary>  

This project transformed sales data into an **interactive Power BI dashboard** to track order and revenue performance across:  

- Geographic territories: *Europe, North America, Pacific*  
- Product categories: *Bikes, Components, Clothing, Accessories*  
- Order statuses and financial metrics: *Revenue, Tax, Freight*  

</details>  

<details>  
<summary><strong>📊 Key Results (click to expand)</strong></summary>  

- 💰 **$30.09M** Total Revenue (1,465 orders)  
- 🚴 **Bikes dominated** → 1,188 orders (Top category)  
- 🌍 **Europe** → Highest-performing region  
- 🚚 **$915.97K** Total Freight cost  
- 💳 **$33.93M** Total Due (financial obligations)  

</details>  

---

## 📊 Main KPIs  

| KPI | Value |
|-----|-------|
| 💰 Total Revenue | **$30.09M** |
| 💳 Total Due (Financial Obligation) | **$33.93M** |
| 🚚 Total Freight | **$915.97K** |
| 📦 Number of Orders | **1,465** |
| 🏆 Best Performing Category | **Bikes (1,188 orders)** |
| 📉 Lower Performing Category | **Accessories (503 orders)** |
| 🌍 Top Performing Region | **Europe** |
| 🕒 Time Trends | Revenue & orders by month (2013–2014) |
| 📊 Order Status Segmentation | Breakdown of orders by status |

---

## ⚙️ Process  

1. Imported raw data into **Power BI**  
2. Cleaned & transformed data using **Power Query**  
3. Built a **Star Schema** for relationships  
4. Created **DAX measures** for KPIs and metrics  
5. Designed interactive visuals, slicers, and filters  

---

## 📐 Data Model  
![Data Model](Project%20Description/Screenshot%20(47).png?raw=true)  

---

## 📈 Dashboard Preview  
<img src="Project Description/Screenshot (44).png?raw=true" width="1000">  
<img src="Project Description/Screenshot (45).png?raw=true" width="1000">  

---

## 🔍 Key Insights  

1. 🚴 **Bikes dominate revenue** → 1,188 orders (81% of total) → heavy reliance on one product category  
2. 🌍 **Europe leads** → strongest region in both orders & revenue  
3. 🚚 **Freight costs significant** → $915.97K (~3% of revenue), impacting profitability  
4. 📅 **Seasonal demand patterns** → clear monthly fluctuations (2013–2014)  
5. 💳 **Revenue gap** → $3.84M difference (Total Due $33.93M vs Revenue $30.09M) → possible discounts or collection issues  

---

## 💡 Conclusion  

- 📌 Identified **revenue concentration** in Bikes (81% of orders)  
- 📌 Highlighted **Europe** as the dominant market  
- 📌 Exposed **freight costs** for potential optimization  
- 📌 Seasonal trends useful for **inventory planning**  
- 📌 Found **revenue leakage** ($3.84M gap: Total Due vs Revenue)  

---

## 🧰 Tools Used  
- **Power BI Desktop**  
- **Power Query**  
- **DAX**  
- **Excel (for data prep)**  
