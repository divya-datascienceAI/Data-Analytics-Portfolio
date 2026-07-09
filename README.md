# Data-Analytics-Portfolio
## Sales Performance and Revenue Analytics
## 1. Business Requirement

The business wanted to understand overall sales performance accross different regions,segment,category,sub-category and time periods.
The key goal is to identify:

- Which Category and regions generate the highest revenue
- Areas with low profitability
- Whether discounts affects profit
- What is the average days taken to ship the product
- What is the higgest number of category products sold
- Who are the top customer
- Monthy Sales trend for forecasting
- Factor affecting overall profit

This analysis helps management improve decision-making and increase revenue.

---
## 2. Dataset Overview

The dataset Contains:

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country/Region
- City
- State/Province
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

Source: Kaggle / Sample Superstore dataset

---
## 3. Data Cleaning & Preperation

Performed the following Steps:

- Removed Duplicates
- Handled missing values
- Converted date columns into proper format
- Created calculated columns(Order month, Order Year,Ship month,Ship year,Days to ship,Profit status)

Tools used: Power BI(Power Query),Excel

---
## 4. Data Analysis Approach

The analysis was performed using:

- DAX measures for KPIs (Total sales,Total Profit,Total Quantity,Total orders,Total Loss,Profit Margin,Avg sales by product,Avg profit by product,Avg order value,Avg shipping days,Sales per customer,Loss order)
- Time series analysis for monthly trends
- Regional,category comparison for performance evaluation
- Category-wise profit and loss breakdown
- Performed Sales analysis by region ,product and Profitability to identify top nad underperforming segments
- Evaluated discount impact accross categories to asses their impact on profitability and pricing strategy

---
## 5. Key Insights

- The Technology category generated the highest overall revenue, while within sub-categories, Chairs contributed the highest revenue; however, Copiers were the most profitable sub-category.
- Categories with higher discounts showed lower profitability compared to products with lower discount rates, indicating a negative impact of heavy discounting on profit margins.
- Over the 3-year period, sales consistently peaked in the month of September, indicating a seasonal demand pattern.
- Most transactions generated revenue below 7K and profit below 2K across all regions, showing that the business is driven by a high volume of low-value orders.
- Based on quantity sold, Office Supplies emerged as the highest-selling category.
- The West region contributed the highest overall revenue and profit compared to other regions.
- December recorded the highest profitability among all months, making it the most profitable month of the year.

---
## 6. Reccomendations

- Focus marketing and strategic investments on the Technology category, as it generates the highest revenue and shows strong profitability potential.
- Prioritize scaling Copiers (high-profit sub-category) while reviewing pricing and cost structure of high-revenue but lower-profit products like Chairs.
- Reduce excessive discounting across categories, as high discounts are directly linked to lower profitability. Instead, apply targeted or seasonal discount strategies.
- Strengthen inventory and marketing efforts around September and December, as these months show peak sales and profitability trends.
- Optimize pricing strategy for low-value transactions (below 7K revenue and 2K profit) by encouraging bundle sales or upselling to improve order value.
- Increase focus on the West region, as it consistently outperforms other regions in both revenue and profit generation.
- Promote Office Supplies strategically, since they lead in quantity sold, but evaluate ways to improve their profit contribution.
- Expand product visibility in low-performing regions by leveraging digital marketing, localized offers, and improved distribution strategies.

---

## 7. Tools used

- Excel
- Power BI
- Power Query
- Dax

---

## 8. Conclusion

This project provides actionable insights into sales performance and helps stakeholders optimize strategy, improve profitability, and make data-driven decisions.

