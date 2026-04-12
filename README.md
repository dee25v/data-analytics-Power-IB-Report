# 📊 Data Analytics Power BI Report

## 📌 Project Overview

This project focuses on transforming raw business data into meaningful insights using Power BI. The goal was to design an interactive dashboard for a retail company to support data-driven decision-making.

The report provides insights into:

* Overall business performance
* Customer behaviour
* Product performance
* Regional sales distribution

---

## 🛠️ Tools Used

* Microsoft Power BI
* Power Query (data transformation)
* DAX (Data Analysis Expressions)

---

## 📂 Dataset

The dataset consisted of four main tables:

* Orders (fact table)
* Products (dimension table)
* Customers (dimension table)
* Stores (dimension table)

---

## 🔄 Data Preparation

The following transformations were applied:

* Removed unnecessary columns (e.g. Card Number)
* Split date and time columns
* Fixed data types (e.g. converting text to numbers)
* Cleaned inconsistent values
* Combined multiple customer files into one dataset

---

## 🧱 Data Modelling

A star schema was created:

* Orders connected to Products, Customers, Stores, and Date tables
* A custom Date table was created for time analysis
* Relationships were set as one-to-many

---

## 📊 Key Measures (DAX)

* Total Revenue
* Total Profit
* Total Orders
* Total Customers
* Total Quantity
* Revenue YTD
* Profit YTD

---

## 📈 Report Pages

### 1. Executive Summary

* KPI cards (Revenue, Profit, Orders, Customers)
* Revenue trend over time
* Year filter

### 2. Customer Detail

* Top customers by revenue
* Revenue by region
* Customer-level filtering

### 3. Product Detail

* Top-performing products
* Revenue by category
* Quantity analysis

### 4. Store Map

* Geographic revenue distribution
* Regional performance comparison

---

## 🎯 Key Insights

* Identified top-performing regions contributing most revenue
* Highlighted highest-value customers
* Determined best-selling products and categories

---

## 📌 What I Learned

* Building data models using star schema
* Writing DAX measures for business metrics
* Designing interactive dashboards
* Cleaning and transforming raw data
* Creating user-friendly data visualisations

---

## 🚀 Future Improvements

* Add more advanced filters and drill-through functionality
* Improve visual design and branding
* Integrate real-time data sources

---

## 📁 File Structure

* `.pbix` file (Power BI report)
* `README.md`

---

## 📜 License

This project is for educational purposes.
