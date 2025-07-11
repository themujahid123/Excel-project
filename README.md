# Excel-project
# Excel-Based Order Analytics Dashboard | Data Cleaning, Modeling & Insights

This project transforms raw, unstructured order data into a professional-grade analytics dashboard — built entirely in Microsoft Excel.

It covers the full analytics workflow:  
🔹 Data Cleaning: Removing inconsistencies and preparing values (dates, prices, IDs)  
🔹 Data Modeling: Structuring tables into a relational model (Orders ↔ Customers ↔ Products)  
🔹 KPI Development: Calculating Total Revenue, Orders, Delivery Time, and Customer Counts  
🔹 Visualization: Creating interactive dashboards with pivot charts, slicers  

The objective is to convert flat datasets into meaningful business insights such as:
- Which product categories are doing well?
- Which cities generate the most orders?
- How long does delivery typically take across locations?
## 📁 Dataset Overview

The dataset is organized into three core sheets, each serving a specific role in the data model:

### 1. `orders`
- Contains transaction-level data for each customer order
- Key fields:
  - `Order_ID`, `Customer_ID`, `Product_ID`
  - `Quantity`, `Order_Date`, `Delivery_Date`
  - `Location`, `Occasion`, `Month`, `Hour`
  - Calculated fields: `date diff` (delivery time), `products.Price (INR)`

### 2. `products`
- Lookup table for product information
- Key fields:
  - `Product_ID`, `Product_Name`, `Category`, `Price (INR)`, `Occasion`, `Description`

### 3. `customers`
- Contains customer demographic and contact data
- Key fields:
  - `Customer_ID`, `Name`, `City`, `Gender`, `Contact_Number`, `Email`, `Address`

These tables are used to model relationships between **sales, product information, and customer behavior**, enabling a comprehensive dashboard in Excel.

## 📊 Key KPIs and Business Questions Answered

The dashboard focuses on high-impact business metrics, all calculated using Excel formulas, pivot tables, and dynamic references.

### 📌 KPIs Included
- **Total Orders** – Number of transactions completed  
- **Total Revenue** – Sum of product price × quantity  
- **Total Customers** – Unique customers placing orders  
- **Average Delivery Time** – Based on difference between order and delivery dates  
- **Top-Selling Product** – By quantity or revenue  
- **Sales by Occasion and Category** – To track seasonal trends  





