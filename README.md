# Superstore Sales & Profit Optimization Analysis
Analysis of retail sales and profitability data from 2015 to 2018.

This project focuses on a comprehensive analysis of historical sales and profit data to identify hidden operational challenges in marketing and pricing policies, delivering data-driven recommendations to maximize net profit.

## 🚀 Key Results & Insights

### 📊 1. Concentration Analysis (Pareto Principle)
* **Products:** It was revealed that **395 out of 793 products** generate **80% of the total revenue**.
* **Customers:** **185 out of 793 customers** provide **80% of the total sales turnover**.
* *Business Insight:* The company should focus its marketing efforts on retaining these top-tier customers and optimizing stock levels specifically for the core product group.

### 🔍 2. Deep-Dive Profitability Analysis: The "Tables" Case
During data aggregation, a critical loss-making category was discovered — **Tables (total net loss exceeding -$17,725)**. A detailed investigation using descriptive statistics unfolded a systemic issue:
* **The Discount Problem:** Without any discount (Discount = 0%), selling tables is highly profitable, generating an average profit of **+$184.39** per transaction.
* However, as soon as a 20% discount is applied, profitability drops below zero. At aggressive discount rates of **40-50%**, the company loses between **$215 and $239 on every single table sold**.
* **Geographic Impact:** The heaviest net losses were recorded in major metropolitan areas: New York City (-$3,542) and Philadelphia (-$2,588).

## 💡 Strategic Business Recommendations
1. **Implement a Strict Discount Cap:** Limit the maximum discount on the "Tables" category to 10%, or completely exclude furniture from global promotional marketing campaigns.
2. **Review Logistics & Shipping Fees:** Re-evaluate shipping costs for oversized items in New York and Philadelphia, or pass a portion of the delivery expenses onto the buyers.

## 🛠 Tech Stack & Methods
* **Python** (Pandas, NumPy, Matplotlib/Seaborn)
* **Methods:** Exploratory Data Analysis (EDA), Data Cleaning & Type Conversion, Advanced Grouping & Aggregation (`groupby`, `.agg()`), Pareto Analysis (Cumulative Share calculation).
