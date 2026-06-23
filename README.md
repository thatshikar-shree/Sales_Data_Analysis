# Sales Data Analysis & Profit Optimization

## Objective
Analyze sales data to identify key factors affecting profit, understand
the impact of discounts, and build a machine learning model to predict profit.

## Problem Statement
- Analyze sales data to understand business performance
- Identify factors affecting profit and revenue
- Study the impact of discounts on profitability
- Provide data-driven business recommendations
- Build a predictive model for sales

## Dataset
- **Source:** sales_data.xlsx
- **Features:** Order Date, Region, Category, Product Name,
  Sales, Profit, Discount, Quantity

## Tools & Libraries
- **Data Handling:** Python, Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn (Linear Regression)

## Project Workflow
1. Load & Understand Dataset
2. Data Cleaning (missing values, duplicates)
3. Feature Engineering (Profit Margin, Year)
4. Exploratory Data Analysis (EDA)
5. Machine Learning — Profit Prediction
6. Business Insights & Conclusion

## Key Analyses
- Sales by Region
- Profit by Category
- Discount vs Profit (scatter analysis)
- Correlation Heatmap
- Yearly Sales Trend
- Top 10 Loss-Making Products
- Discount Range Impact on Profit

## ML Model
| Model | Target Variable |
|-------|----------------|
| Linear Regression | Profit |

**Features used:** Sales, Discount, Quantity

**Key Findings:**
- Sales positively impacts profit (+0.227)
- Discount strongly reduces profit (-203.10)
- Higher quantity can reduce profit in some cases

## Business Recommendations
- Optimize discount strategy to protect profit margins
- Focus on high-profit categories
- Revisit pricing for loss-making products

