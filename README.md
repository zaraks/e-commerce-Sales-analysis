# E-commerce Store Data Analytics Project

## Overview
This project performs a comprehensive analysis of an e-commerce store’s sales and profit data, containing over **10,000 entries**. The aim is to uncover insights on sales trends, product performance, and customer segments to support data-driven business decisions.

---

## Project Overview
The analysis focuses on understanding:
- Monthly sales and profit trends
- Performance by product **category** and **subcategory**
- Customer segment contribution to sales and profit
- Profitability and efficiency metrics such as **sales-to-profit ratio**

The project was implemented in **Python using Jupyter Notebook**, combining data cleaning, exploration, aggregation, and visualizations to derive actionable insights.

---

## Data Summary
- Dataset contains transactional data of an e-commerce store, including:
  - Order Date
  - Product Category & Subcategory
  - Sales
  - Profit
  - Customer Segment
- The dataset has **over 10,000 entries** with no missing values.
- Key derived features:
  - **Order Month, Order Year, Order Day** extracted from Order Date
  - Aggregated metrics using `groupby` for analysis by month, category, subcategory, and segment

---

## Exploratory Data Analysis (EDA) Using Python
The following steps were performed during EDA:

1. **Data Inspection**  
   - Loaded dataset using `pandas` and examined data structure (`data.info()`, `data.head()`).
   - Verified no missing/null values were present.

2. **Feature Engineering**  
   - Extracted time-related features: Order Month, Order Year, Order Day
   - Ensured chronological ordering for month-wise analysis

3. **Aggregation & Grouping**  
   - Used `groupby` to summarize sales and profit by:
     - Month
     - Category
     - Subcategory
     - Customer Segment

4. **Visualizations**  
   - Line graphs for **monthly sales and profit trends**
   - Bar charts for **category and subcategory analysis**
   - Pie charts to show **customer segment contributions**
   - Combined graphs to compare **sales vs. profit**  

---

## Tools & Libraries
- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation and aggregation
- **Plotly** – interactive visualizations  
  - `plotly.express` 
  - `plotly.graph_objects`
  - `plotly.io`
  - `plotly.colors`  
- Plotly templates: `pio.templates.default = 'plotly_white'`
https://zaraks.github.io/e-commerce-Sales-analysis/html/e-commerce_data_analysis (2).html






