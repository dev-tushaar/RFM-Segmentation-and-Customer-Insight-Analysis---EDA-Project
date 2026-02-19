# 📊 RFM Customer Segmentation & Strategic Marketing Analysis

This project applies **RFM (Recency, Frequency, Monetary) Analysis** to segment customers based on purchasing behavior and generate actionable business insights. The goal is to transform transactional data into strategic intelligence that improves customer retention, marketing efficiency, and revenue growth.

## 🔍 Business Objective

Many businesses treat customers uniformly, resulting in inefficient marketing spend and missed revenue opportunities. This project identifies high-value customers, churn risks, and growth opportunities using behavioral segmentation.

## 🛠 Methodology

1. **Data Cleaning & Preparation**

   * Removed invalid/duplicate records
   * Converted date columns
   * Structured dataset for analysis

2. **RFM Calculation**

   * **Recency**: Days since last purchase
   * **Frequency**: Number of transactions
   * **Monetary**: Total revenue per customer

3. **Quantile-Based Scoring**

   * Assigned scores (1–5) to normalize distribution
   * Created RFM segment codes (e.g., 555 = Champions)

4. **Customer Segmentation**
   Customers were categorized into:

   * Champions
   * Loyal Customers
   * Potential Loyalists
   * At Risk
   * Lost

## 📈 Key Insights

* Revenue follows the Pareto principle — a small group of high-value customers contributes the majority of revenue.
* A large share of customers are one-time buyers, highlighting retention opportunities.
* At Risk and Lost segments show strong churn signals.
* Monetary distribution is positively skewed, emphasizing the importance of premium customer protection.

## 🧠 Strategic Recommendations

* Premium engagement and exclusivity for Champions
* Loyalty programs to increase repeat purchases
* Reactivation campaigns for churn-risk customers
* Cross-selling bundles to increase Average Order Value (AOV)
* Seasonal and geo-targeted campaigns to optimize ROI

## 🛠 Tools Used

Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

This project demonstrates how customer behavioral analytics can directly support data-driven marketing and product strategy decisions.
