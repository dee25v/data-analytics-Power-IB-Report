# 📊 Data Analytics Power BI Report

![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat\&logo=github\&logoColor=white)

---

## 📌 Project Overview

This project was completed as part of a data analytics case study for a medium-sized international retailer. The goal was to transform raw sales data into actionable insights using Microsoft Power BI.

The final solution is a multi-page interactive dashboard providing insights into:

* Business performance
* Customer behaviour
* Product performance
* Geographic sales distribution

---

## 🛠️ Tools & Technologies Used

* Microsoft Power BI Desktop
* Power Query (Data Transformation)
* DAX (Data Analysis Expressions)
* CSV Data Sources
* Data Modelling (Star Schema)

---

## ⚙️ Project Workflow

### 🔹 1. Data Import

* Imported datasets (Orders, Products, Stores, Customers) from CSV files
* Loaded data into Power BI using the **Get Data** feature

📸 *Screenshot Placeholder – Data Import*
*Add your screenshot here*

---

### 🔹 2. Data Cleaning & Transformation

* Removed unnecessary columns (e.g. Card Number)
* Split date and time columns into separate fields
* Fixed incorrect data types (e.g. Product Quantity from text to number)
* Cleaned inconsistent region values
* Combined multiple customer files into one dataset

📸 *Screenshot Placeholder – Power Query Transformations*
*Add your screenshot here*

---

### 🔹 3. Data Modelling

* Built a **star schema**
* Created relationships between:

  * Orders → Products
  * Orders → Customers
  * Orders → Stores
* Created a custom **Date table using DAX**
* Marked Date table for time intelligence
* Created a **Measures Table** for calculations

📸 *Screenshot Placeholder – Data Model View*
*Add your screenshot here*

---

### 🔹 4. DAX Measures

Created key business metrics:

* Total Revenue
* Total Profit
* Total Orders
* Total Customers
* Total Quantity
* Revenue YTD
* Profit YTD

📸 *Screenshot Placeholder – Measures Table*
*Add your screenshot here*

---

## 📊 Dashboard Pages

### 🔹 1. Executive Summary

* KPI cards (Revenue, Profit, Orders, Customers)
* Line chart showing revenue trends over time
* Year slicer for filtering

📸 *Screenshot Placeholder – Executive Summary Page*
*Add your screenshot here*

---

### 🔹 2. Customer Detail Page

* Table of top customers (sorted by revenue)
* Bar chart showing revenue by region
* Customer slicer for filtering

📸 *Screenshot Placeholder – Customer Page*
*Add your screenshot here*

---

### 🔹 3. Product Detail Page

* KPI cards (Revenue, Profit, Quantity)
* Table showing top products (Product Code)
* Bar chart showing revenue by category
* Quantity analysis chart
* Product slicer

📸 *Screenshot Placeholder – Product Page*
*Add your screenshot here*

---

### 🔹 4. Stores Map Page

* Map visual showing revenue distribution by location
* Bar chart comparing regional performance
* KPI cards summarising store performance

📸 *Screenshot Placeholder – Map Page*
*Add your screenshot here*

---

## 🎯 Key Insights

* Identified top-performing regions generating the highest revenue
* Highlighted high-value customers contributing most to sales
* Determined best-performing products and categories
* Visualised geographic performance across store locations

---

## 📚 Skills Demonstrated

* Data cleaning and transformation using Power Query
* Data modelling using star schema design
* Writing DAX measures for business metrics
* Building interactive dashboards
* Creating user-friendly visualisations

---

## 🚀 Future Improvements

* Add navigation buttons between pages
* Implement advanced DAX calculations
* Improve dashboard design with themes and icons
* Add drill-through functionality

---

## 📁 Files

* Power BI Report (`.pbix`)
* README.md

---

## 📜 License

This project is for educational purposes.
