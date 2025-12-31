# 📊 Superstore Sales Analysis | Power BI

## 📌 Project Overview
This project is an **end-to-end Power BI Sales Analysis solution** built using the Superstore dataset.  
The objective of this project is to demonstrate **real world Business Intelligence skills**, including data cleaning, data modeling, DAX measures, and dashboard development.

The project follows **industry best practices** by converting a raw flat file into a **Star Schema**, creating business focused KPIs, and presenting insights through a clean, interactive dashboard.

---

## 🧹 Data Loading & Cleaning (Power Query)
- Loaded the Superstore dataset from Excel
- Cleaned and transformed data using **Power Query**
- Handled:
  - Data type corrections
  - Column renaming
  - Data consistency issues
- Prepared data for efficient modeling and analysis

---

## 🧱 Data Modeling – Star Schema
The original flat file was converted into a **Star Schema** to improve performance, clarity, and scalability.

### ⭐ Fact Table
- **Orders**
  - Sales
  - Profit
  - Quantity
  - Discount
  - Order ID

### ⭐ Dimension Tables
- **Customer** – Customer Name, Segment
- **Product** – Category, Sub-Category, Product Name
- **Return** – Returned orders information
- **People** – Regional managers
- **Order_Date** – Order date attributes
- **Ship_Date** – Shipping date attributes

✔ Relationships created using **best practices** for Power BI data modeling.

---

## 📐 DAX Measures & KPIs
Created reusable **DAX measures** to track key business metrics.

### 🔢 Key KPIs
- Total Sales  
- Total Profit  
- Profit Margin (%)  
- Total Orders  
- Total Quantity Sold
- Avg Order Value 

These KPIs are used consistently across all report pages.

---

## 📊 Dashboard Development
Developed a **interactive Power BI dashboard** focused on business insights.

### 1️⃣ Overview Page
- High-level KPIs (Sales, Profit, Orders, Quantity)
- Overall sales trends
- Executive friendly summary view

### 2️⃣ Sales Analysis Page
- Category & SubCategory performance
- Product level insights
- Sales distribution and comparison analysis

🎯 Features used:
- Slicers for interactivity
- Drill down analysis
- Clean and consistent visual design

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Star Schema Data Modeling**

---

## 📁 Repository Structure
```
Superstore-PowerBI-Sales-Analysis/
│
├── data/
│ └── superstore_dataset.xlsx
│
├── powerbi/
│ └── Superstore_Sales_Analysis.pbix
│
├── Visuals/
│ ├── dashboard_overview.png
│ ├── sales_analysis.png
│ └── data_model.png
│
├── video-demo/
│ └── superstore_powerbi_demo.mp4
│
├── README.md

```

---

## 🎯 Project Use Case
This dashboard helps:
- Business users understand sales performance
- Identify high and low performing products
- Track profitability and sales trends
- Support data driven decision-making

---

## 🚀 Key Learnings
- Data cleaning using Power Query
- Converting flat files into a Star Schema
- Writing business-ready DAX measures
- Designing clear, insight-driven Power BI dashboards

---

## 👤 Author
**MIT TRIVEDI**  
Data science Professional  
📧 Email: trivedimit04@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mit-trivedi-8714a5344/)  
🔗 [Portfolio](https://github.com/trivedimit/) 

