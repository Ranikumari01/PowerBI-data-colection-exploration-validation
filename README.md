# 📊 iPhone Sales Analysis Dashboard (Power BI)

## 📁 Datasets Used:
1. `dim_stores.csv` – Information about store locations.
2. `fact_sales_iPhone14.csv` – iPhone 14 sales data for Sep-Nov 2022.
3. `fact_sales_iPhone15.csv` – iPhone 15 sales data for Sep-Nov 2023.

## 📌 Objective:
To compare iPhone 14 and iPhone 15 sales performance across countries and provide insights into:
- Absolute sales difference (variance)
- Percentage sales difference
- Top 10 countries with the highest variance in sales

## 🛠️ Steps Performed:
- Imported datasets and created relationships
- Merged sales data for both models
- Created calculated columns for:
  - Absolute Variance: `ABS([iPhone15] - [iPhone14])`
  - Percentage Variance: `(([iPhone15] - [iPhone14]) / [iPhone14]) * 100`
- Visualized:
  - Sales comparison bar charts
  - Country-wise variance table
  - Top 10 countries with max variance

## 📷 Sample Dashboard View:
![image](https://github.com/user-attachments/assets/b63184c6-8334-49e9-bf9c-07978f21b6bc)


---



## 🛠️ Tools:
- Power BI Desktop
- DAX for calculated measures
