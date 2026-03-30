 Bike Sales Data Cleaning & Analysis — MS Excel Project

This is a beginner-friendly Excel project where I worked on a raw, unclean bike sales dataset. The goal was to clean the data, apply useful formulas, and create a summary report — all inside one Excel workbook.

---

📂 What is Inside the Workbook

The workbook has **4 sheets**, each serving a different purpose:

| Sheet | Description |
|---|---|
| `bike_sales_UNCLEAN` | The original raw dataset with errors and missing data |
| `bike_sales_CLEAN` | The cleaned and corrected version of the same data |
| `Formula and Functions` | A sheet showing different Excel formulas applied to the data |
| `Pivot Table` | A summary report built from the cleaned data |

---

## 📋 About the Dataset

- **Total Rows:** 95 records
- **Total Columns:** 16 columns
- **Data Includes:** Sales Order ID, Date, Customer Age, Gender, Country, State, Product Category, Product Description, Order Quantity, Unit Cost, Unit Price, Profit, Cost and Revenue

---

 Problems Found in the Raw Data

When I first opened the dataset, it had several issues:

- **12 missing dates** — some cells showing `#NAME?` formula errors
- **14 missing Age Group** values
- **8 missing Customer Age** values
- **5 missing Order Quantity** values
- **1 missing Product Description**
- **Inconsistent text casing** — for example `BIKES`, `Bikes` and `bikes` all in the same column
- **Extra spaces** in Country and State names — like `' Australia '` or `'  CALIFORNIA'`

---

 🧹 How I Cleaned the Data

I used the following Excel functions to fix the issues:

- **`TRIM()`** — Removed all extra spaces from Country and State columns
- **`PROPER()`** — Standardized text so everything follows the same casing format
- **`IFERROR()`** — Replaced broken formula errors with correct values

After cleaning, the dataset was reduced to **78 valid rows** with consistent and accurate information.

---

 Formulas and Functions Used

I created a separate sheet to showcase different Excel formulas using the cleaned data:

| Formula | How I Used It |
|---|---|
| `VLOOKUP` | Searched and matched sales records using Order ID |
| `XLOOKUP` | A more flexible version of VLOOKUP for the same purpose |
| `IFS` | Categorized each order's profit as LOW, AVERAGE, HIGH or VERY HIGH |
| `IF` | Labeled each order as GOOD or NOT GOOD based on profit |
| `AND` | Checked multiple conditions to mark orders as PREMIUM or STANDARD |
| `FILTER` | Pulled only the rows that matched a specific country |
| `CHOOSECOLS` | Removed unwanted columns from the FILTER results |

---

## 📊 Pivot Table — Summary Report

Using the clean data, I built a **Pivot Table** that summarizes:

- Total sales and profit **by Country**
- Breakdown of orders **by Product Category**
- Customer distribution **by Age Group**

This gives a quick overview of where sales are coming from and which products perform best.

---

## 🎯 What I Want to Showcase

This project shows that I can:

- Look at messy, real-world data and fix it properly
- Use Excel formulas to automate checks and categorization
- Pull and filter specific data when needed
- Build a simple report using Pivot Tables
- Keep data clean, consistent and easy to read

These are the exact skills needed for roles involving **data entry, catalog management, and quality checking.**

---

## 🛠 Tools Used

- **Microsoft Excel**
  

---

## 📁 How to Open

Download the `.xlsx` file from this repository and open it directly in **Microsoft Excel** to explore all 4 sheets.
