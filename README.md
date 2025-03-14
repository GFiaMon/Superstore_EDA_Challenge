# Superstore Sales Performance Analysis

![EDA](https://img.shields.io/badge/Analysis-Exploratory%20Data%20Analysis-blue)
![Business](https://img.shields.io/badge/Focus-Business%20Analytics-orange)

An end-to-end Exploratory Data Analysis (EDA) of a retail superstore's sales data (2014–2017) to uncover actionable insights for improving profitability and customer retention.

---

## 📌 Key Questions Explored
1. **Sales Trends**: How do sales vary monthly? Are there seasonal patterns?
2. **Product Margins**: Which categories have the best/worst profit margins?
3. **Regional Performance**: Which regions are most profitable? Are high sales always profitable?
4. **Customer Segmentation**: Who are the most valuable customers? How can we retain at-risk groups?
5. **Shipping Modes**: How does shipping mode affect profitability?

---

## 📂 Dataset
- **Source**: Sample Superstore dataset (2014–2017).
- **Columns**: `Order Date`, `Sales`, `Profit`, `Region`, `Category`, `Ship Mode`, `Customer ID`, etc.
- **Scope**: 9,994 transactions across 4 regions (West, East, Central, South).

---

## 🔍 Key Findings
### 1. Sales Trends
- **Peaks**: December (holiday season) and March (fiscal year-end).
- **Dips**: January (post-holiday slump).
- **YOY Growth**: +30% in 2016, +20% in 2017.

### 2. Product Margins
- **Best**: Technology (15.6% margin).
- **Worst**: Furniture (3.9% margin).

### 3. Regional Performance
- **Top Region**: West (highest sales *and* profit).
- **Struggling Region**: Central (7.9% margin despite moderate sales).

### 4. Customer Segmentation
- **Loyal Customers**: 25.85% of customers drive 52% of revenue.
- **At-Risk Customers**: 24.72% of customers need retention efforts.
- **High Spenders**: No customers in this segment (untapped opportunity).

### 5. Shipping Modes
- **Most Profitable**: Second Class (15% margin).
- **Highest Profit/Order**: First Class ($31.84/order).

---

## 🚀 Business Recommendations
1. **Optimize Shipping**:
   - Promote **Second Class** for better margins.
   - Reserve **First Class** for high-value orders.
   - **Impact**: Estimated $27K annual profit gain.

2. **Retain At-Risk Customers**:
   - Launch personalized discounts/loyalty programs.
   - **Impact**: Save $46K in potential revenue loss.

3. **Leverage Seasonal Peaks**:
   - Boost inventory/marketing in **December** and **March**.
   - **Impact**: Generate $4.8K additional revenue.

---

## 💻 Code & Usage
### Libraries Used
- `dplyr`, `ggplot2`, `readr`, `zoo`

### Run the Analysis
```r
# Install packages
install.packages(c("dplyr", "ggplot2", "readr", "zoo"))

# Load data and scripts
source("superstore_analysis.R")