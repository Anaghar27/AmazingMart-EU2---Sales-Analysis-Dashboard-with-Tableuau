# 📊 AmazingMart EU2 - Sales Analysis Dashboard

This repository contains a Tableau dashboard and supporting dataset used to analyze the sales performance of AmazingMart EU2 across various regions in Europe.

## 📁 Files Included

- `AmazingMartEU2.xlsx`: Contains three sheets:
  - `ListOfOrders`: Main dataset with 4,117 order records across 10 columns.
  - `OrderBreakdown`: Item-level breakdowns of orders totaling 8,047 rows.
  - `SalesTargets`: Target values for sales and profit across segments.

- `Sales_Profit_Europe.twbx`: Packaged Tableau workbook containing interactive visualizations and dashboards.

## 📄 Dataset Description

1. **ListOfOrders**
   - Contains high-level order details including:
     - `Order ID`, `Order Date`, `Customer Name`, `City`, `Country`, `Region`, `Segment`, `Ship Date`, `Ship Mode`, and `State`.

2. **OrderBreakdown**
   - Provides item-level information for each order, potentially including fields like `Product Name`, `Quantity`, `Sales`, `Profit`, `Discount`, etc.

3. **SalesTargets**
   - Stores predefined targets for sales and profit across different customer segments.

## 📈 Key Visual Insights (from Tableau Dashboard)

Based on the Tableau workbook, here are some key insights derived:

- **Top Performing Countries**
  - The United Kingdom and France contribute the highest total sales.
  - Germany has consistent sales but lower profit margins due to higher discounts.

- **Segment Performance**
  - The `Consumer` segment drives the majority of sales.
  - `Corporate` and `Home Office` segments show potential for growth with higher average profits per transaction.

- **Shipping Mode Impact**
  - Orders shipped via `Priority` and `Second Class` modes result in higher profits.
  - `Economy` shipping is the most used but contributes less to profitability.

- **Seasonal Trends**
  - Sales peak during Q2 and Q4, indicating possible seasonal campaigns or higher demand during these periods.
  - Lower sales are observed during the first few months of the year.

- **Sales vs. Targets**
  - Some regions and segments consistently exceed their sales targets, notably the Central Europe region.
  - A few regions like Southern Europe fall short, requiring targeted marketing interventions.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   https://github.com/Anaghar27/AmazingMart-EU2---Sales-Analysis-Dashboard-with-Tableuau.git
