# Data-Analyst-PortfolioProject
  ## [Capstone Project](https://github.com/Vidit-Goyal/Data-Analyst-PortfolioProject/blob/main/Capstone%20Project/Vendor%20Performance%20Analysis.docx)

  Retail Vendor Performance Analysis - Vendor, Inventory & Sales Analysis | SQL, Python & Power BI Insights

Analyzing vendor efficiency and profitability to drive strategic purchasing and inventory decisions using SQL, Python, and Power BI

🔍 Overview

Developed a complete data analytics pipeline to evaluate vendor performance, pricing efficiency, and inventory dynamics in the retail sector.

- SQL for ETL and data preparation

- Python (Pandas, Matplotlib, Seaborn, SciPy) for analysis & hypothesis testing

- Power BI for interactive dashboards and insights presentation

💼 Business Problem
Retail businesses risk profit losses due to:

- Underperforming brands with inefficient pricing

- Over-reliance on a few major vendors

- Poor bulk purchasing strategies

- High holding costs from slow-moving stock

📊 Dataset

- Source: Kaggle retail sales dataset

- Data cleaned and structured for vendor-level performance analysis

🛠 Data Cleaning & Preparation

- Removed transactions with Gross Profit ≤ 0, Profit Margin ≤ 0, or Sales Quantity = 0

- Created vendor-level KPI tables & merged lookup data

- Handled outliers (e.g., freight costs up to $257K) and large price variations

🔬 Exploratory Data Analysis & Key Insights

- Brands for Promotions: 198 brands with low sales but high margins → promotion opportunity

- Vendor Concentration Risk: Top 10 vendors = 65.7% of purchases

- Bulk Purchasing Benefit: 72% cost savings per unit for large orders

- Inventory Turnover Issue: $2.71M worth of unsold inventory

- Profitability Analysis:

   - High-selling vendors → Mean Margin: 31.17%

   - Low-selling vendors → Mean Margin: 41.55%

   - Hypothesis testing confirms statistically significant difference

## 📈 Dashboard
[**View Interactive Power BI Dashboard**](https://app.powerbi.com/groups/me/reports/3891a8e9-f979-4059-93bf-dd8c859a9dc8/1bbcb957271c3e1c65d7?experience=power-bi)

- Vendor-wise sales & profit margins

- Inventory turnover heatmaps

- Bulk purchase cost savings visualization

- Brand performance comparison

✅ Final Recommendations

- Diversify vendor base to reduce dependency risk

- Optimize bulk purchasing to maximize cost savings

- Reprice or promote slow-moving, high-margin brands

- Clear stagnant inventory strategically

- Improve marketing reach for low-performing vendors


# [Health Insurance Data Analysis – SQL Project](https://github.com/Vidit-Goyal/Data-Analyst-PortfolioProject/blob/main/SQL%20Projects/SQL%20Project%202.docx)

**Analyzing policyholder, policy, and claim data to improve operational performance, customer segmentation, and profitability.**

---

## 📌 Overview
A health insurance company aims to **enhance operational insights** by analyzing historical data related to **policyholders, policies, and claims**.  
This project uses SQL to:
- Identify performance trends
- Improve customer segmentation
- Support data-driven decision-making

---

## 💼 Business Problem
Key challenges for the business include:
- Understanding claim payout patterns
- Detecting policy types with higher risks or profitability
- Reducing claim rejection rates
- Enhancing retention strategies for high-value customers

---

## 📊 Dataset
Source: Kaggle Healthcare dataset

The analysis was conducted on **three key datasets**:  

**Policyholders**
- `policyholder_id`, `full_name`, `gender`, `date_of_birth`, `email`, `phone`

**Policies**
- `policy_id`, `policyholder_id`, `policy_type`, `start_date`, `end_date`, `premium_amount`, `status`

**Claims**
- `claim_id`, `policy_id`, `claim_date`, `claim_amount`, `claim_status`, `claim_type`

---

## 🛠 Tools & Technologies
- **SQL** (Joins, Aggregations, Filtering, Conditional Logic)
- **MySQL** for querying
- **Data Visualization Tool** *(optional for presenting results)*

---

## 🔍 Key Analysis & SQL Queries
1. **Highest Average Claim Amount by Policy Type**
2. **Average Premium and Claim Payout Ratio per Policy Type**
3. **Rejected Claims in the Last 12 Months by Type**
4. **Top 10 Policyholders by Approved Claim Amount**
5. **Policyholder Count by Gender**
6. **Number of Active Policies**
7. **Claim Approval Rate per Claim Type**
8. **Policy Count by Status**
9. **Average Claim Amount per Claim Type**
10. **Policyholders with Multiple Policies (Total Premium & Claim Amount)**

---

## 📈 Key Insights
- **Profitability Patterns:** Certain policy types show significantly higher claim payout ratios, affecting underwriting margins.
- **High-Value Customers:** Top 10 policyholders have substantial approved claim amounts, ideal for loyalty programs.
- **Claims Management:** Up to **30% reduction in rejected claims** possible by fixing documentation issues for high-rejection claim types.
- **Revenue Growth Potential:** Targeting high-value or loyal customers can increase revenue by **8–10%**.
- **Demographic Segmentation:** Gender-based and behavioral segmentation improves marketing ROI.

---

## ✅ Recommendations
- Standardize documentation for claim types with high rejection rates  
- Automate routine claim evaluations to speed up processing  
- Segment customers by gender, age, or claim behavior for targeted marketing  
- Introduce loyalty programs or bundled benefits for customer retention  

---

## 👤 Author
**Vidit Goyal** – Aspiring Data Analyst / Business Analyst  
📧 [Vidit.goyalccc@gmail.com](mailto:Vidit.goyalccc@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/vidit-goyal/)  
🔗 [Portfolio](https://github.com/Vidit-Goyal/Data-Analyst-PortfolioProject) 
