# Grocery-Sales-Analysis-Using-Excel
This project presents a comprehensive analysis of grocery store sales data using Microsoft Excel. It includes data cleaning, transformation, and visualization through interactive dashboards to uncover key business insights.
# Grocery Sales Dashboard 📊

This repository contains an interactive **Grocery Sales Dashboard** created using **Microsoft Excel**, focused on analyzing grocery product sales across different cities, categories, and customer segments. It utilizes Excel’s powerful data analysis features such as **PivotTables**, **PivotCharts**, **VLOOKUP**, **data cleaning**, and **filtering/sorting** to provide actionable insights.

---

## 📁 Project Contents

- `Grocery_Sales_Dashboard.xlsx`: The main Excel file with all the visualizations and data analysis.
- `dataset/`: Folder containing the original raw dataset used for building the dashboard.
- `images/dashboard_preview.png`: A snapshot of the Excel dashboard.
  
---

## 📊 Data Analysis Overview

### 🔍 Steps Performed:

1. **Data Cleaning & Preparation**:
   - Removed duplicates and empty rows.
   - Standardized column names (e.g., `Product Name`, `Sales Amount`, `City`, `Customer Name`, etc.).
   - Checked and fixed incorrect data types (e.g., converting text-formatted numbers into numeric values).
   - Replaced missing values with appropriate defaults or handled with filtering.

2. **Data Types Handled**:
   - **Text**: Product names, customer names, cities, categories.
   - **Numbers**: Sales, net sales, product quantities.
   - **Dates**: If applicable, parsed date fields correctly for trend analysis.

3. **Data Transformation & Lookup**:
   - Used **VLOOKUP** to:
     - Match category descriptions to product IDs.
     - Associate city sales with region names.
     - Merge supporting information like resistance levels and product classifications.
     
4. **Sorting and Filtering**:
   - Sorted sales data to identify top and bottom performers by product and city.
   - Applied filtering to isolate low-performing SKUs, regions, or product classes.

---

> Filters and slicers are applied across dashboards for interactivity (e.g., by category, class, resistance level).

---

## 🖥️ Dashboard Preview

![Grocery Sales Dashboard](https://github.com/mahajanakshay956/Grocery-Sales-Analysis-Using-Excel/blob/main/Grocery-Sales-Dashboard.png)

---

## 📌 Key Insights Enabled

- Identify top customers and top-selling products
- Track city-wise sales performance
- Examine class-based sales trends across product categories
- Determine the impact of product resistance levels on sales
- Recognize low-performing items for potential discontinuation

---

## 📂 Dataset & Dashboard Files

- 📈 **[Download Excel Dashboard](https://github.com/mahajanakshay956/Grocery-Sales-Analysis-Using-Excel/blob/main/Grocery-Sales-Dashboard.png)**  
- 🗃️ **[Download Dataset File (CSV/XLSX)](https://github.com/mahajanakshay956/Grocery-Sales-Analysis-Using-Excel/blob/main/Akshay_Mahajan_Grocery_Sales_Dashboard.xlsx)**
---

## 🔧 How to Use

1. Download and open `Grocery_Sales_Dashboard.xlsx` in Excel (2016 or later recommended).
2. Navigate through various dashboard sheets and use slicers to explore trends.
3. Examine PivotTables for raw values behind each chart.

---

## 🧠 Excel Features Used

- PivotTables
- PivotCharts
- VLOOKUP
- Data Types (Text, Number, Date)
- Data Sorting and Filtering
- Conditional Formatting (where applicable)
- Named Ranges
- Slicers for interactive filtering
