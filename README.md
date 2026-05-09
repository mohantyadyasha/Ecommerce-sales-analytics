# 🛒 E-Commerce Sales Analytics — End to End Project
![Python](https://img.shields.io/badge/Python-3.9-blue)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 🔍 Problem Statement
An e-commerce company want to understand its sales, identify the top performing products and categories, analyse profit and discover antionable insights to boost revenue growth.

## 📁 Project Structure

| File | Description |
|---|---|
| `Ecommerce_Sales_Analytics.ipynb` | Full analysis notebook — cleaning, EDA, insights |
| `ecommerce.csv` | Cleaned dataset — 9,994 orders |
| `E-Commerce_Dashboard.pbix` | Interactive Power BI dashboard |

## 💡 Key Findings

1. **Technology** is the highest revenue category
2. **Furniture** has the lowest profit margin despite high sales
3. **Heavy discounts above 20%** lead to negative profit
4. **West region** generates the highest overall sales
5. **Q4** consistently shows highest sales — seasonal trend
6. **Tables and Bookcases** are loss-making sub-categories

## 🔬 Project Phases

### Phase 1 — Data Cleaning
- Converted Order Date and Ship Date to datetime format
- Removed unnecessary columns
- Created Shipping Time feature (Ship Date - Order Date)
- Added Month column for time series analysis

### Phase 2 — Exploratory Data Analysis
- Sales and profit by Category and Sub-Category
- Regional performance analysis
- Discount impact on profitability
- Monthly sales trends
- Top 10 profitable and loss-making products

### Phase 3 — Business Insights
- Identified loss-making products and categories
- Discount threshold analysis
- Customer segment performance
- Shipping mode analysis

### Phase 4 — Power BI Dashboard
Interactive dashboard covering:
- **Sales Overview** — total sales, profit, orders KPIs
- **Category Analysis** — performance by category and sub-category
- **Regional Analysis** — sales and profit by region and state
- **Time Analysis** — monthly and quarterly trends

---

## 📊 Dataset

- **Name:** Superstore Sales Dataset
- **Rows:** 9,994 orders
- **Features:** 22 columns
- **Period:** 2014 — 2017
- **Source:** Kaggle Superstore Dataset

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python | Data cleaning and EDA |
| Pandas | Data manipulation |
| Seaborn and Matplotlib | Data visualisation |
| Power BI | Interactive dashboard |

---

## 🎯 Business Recommendations

1. **Stop heavy discounting** on Furniture — discount above 20% causes losses
2. **Focus marketing** on Technology category — highest profit margin
3. **Review Tables and Bookcases** pricing strategy — consistently loss-making
4. **Leverage Q4 seasonality** — increase inventory and marketing budget in Q3
5. **Expand in West region** — highest revenue potential
