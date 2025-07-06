# Online Retail Analytics Dashboard (Power BI)

## 📊 Project Overview

This project provides an interactive *Power BI dashboard* analyzing online retail sales to support the *CEO* and *CMO* in making data-driven decisions about revenue trends, top customers, and expansion strategies.

The analysis answers key business questions:
1. What are the seasonal trends in revenue?
2. Which countries generate the most revenue (excluding the United Kingdom)?
3. Who are the top customers by revenue?
4. Where is the greatest product demand geographically?

---

## 🏪 Data Source

*Online Retail Data Set*

- Contains transactional data from an online store:
  - Invoice details
  - Quantities and prices
  - Customer IDs
  - Country
  - Transaction dates
- Source:
  > Daqing Chen, Sai Liang Sain, and Kun Guo (2012). Data mining for the online retail industry.

---

## 🛠 Tools Used

- *Power BI Desktop*
- Windows Operating System

---

## 🧹 Data Cleaning Steps

Before building the visuals, the data was cleaned to ensure accuracy:

✅ *Quantity Check*
- Removed rows where Quantity < 1

✅ *Unit Price Check*
- Removed rows where UnitPrice < $0

These steps ensured that only valid sales transactions were included in the analysis.

---

## 📈 Visualizations

Each visual is built on a separate tab named after the business question:

### 🔹 Question 1: Monthly Revenue Trends (2011)
- *Line chart* displaying monthly revenue for 2011 to help identify seasonal patterns.

### 🔹 Question 2: Top 10 Countries by Revenue (Excluding UK)
- *Bar chart* highlighting the top 10 revenue-generating countries (excluding United Kingdom).
- Includes quantity sold alongside revenue.

### 🔹 Question 3: Top 10 Customers by Revenue
- *Clustered Column chart* showing top customers by total revenue.

### 🔹 Question 4: Product Demand by Country (Excluding UK)
- *Map visual * illustrating product demand across all countries.
- United Kingdom excluded to focus on expansion opportunities.

---

## 🚀 How to Open the Dashboard

1. *Download the PBIX file:*
   [Download OnlineRetail_Insights_dashboard.pbix](https://github.com/NIHLA098/online-retail-analytics-dashboard/raw/refs/heads/main/OnlineRetail_Insights_dashboard.pbix)

2. Open it with *Power BI Desktop*.

3. Explore each tab to view:
   - Revenue trends
   - Top-performing countries
   - High-value customers
   - Geographic demand insights

---

## 📂 Repository Contents

- OnlineRetail_Insights_dashboard.pbix — Power BI project file
- README.md — Project documentation
- screenshots of insights 

---

## ✨ Key Insights

- Clear seasonal revenue trends in 2011
- High-revenue countries identified (excluding UK)
- A small segment of customers contribute significantly to revenue
- Specific regions show strong demand for expansion

---

## 👤 Author

*Fathima Nihla M*  
 [fathimanihla841@gmail.com](mailto:fathimanihla841@gmail.com)


