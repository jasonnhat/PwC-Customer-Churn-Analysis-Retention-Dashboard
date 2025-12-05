# 📊 PwC Customer Churn Analysis & Retention Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview
This project focuses on the telecommunications industry, where customer retention is critical for profitability. Using a dataset of **7,043 customers**, I performed a comprehensive analysis to identify the key drivers of customer churn. 

The project includes:
1.  **Diagnostic Analytics:** Interactive Tableau dashboards to visualize churn patterns.
2.  **Predictive Modeling:** A Logistic Regression model (85% accuracy) to predict churn risk.
3.  **Strategic Recommendations:** actionable insights to reduce churn and increase Customer Lifetime Value (CLV).

## ❓ Business Problem
The telecommunications industry faces significant revenue loss due to customer attrition. Retaining existing customers is known to be more cost-effective than acquiring new ones. The goal of this analysis was to answer:
* Which demographics and service subscriptions drive churn?
* How do contract types and payment methods impact retention?
* What is the financial impact of current churn rates?

## 📂 Dataset
* **Source:** PwC Virtual Internship (Forage)
* **Volume:** 7,043 Records, 23 Columns
* **Key Fields:** Tenure, Contract Type, Monthly Charges, Payment Method, Tech Support Tickets, Churn Status.

## 📊 Dashboard Visuals
### 1. Customer Profile & Demographics
*An overview of customer distribution by tenure, gender, and subscription type.*
![Customer Profile Dashboard](image_ebc806.png)
*(Note: Replace this text with the actual path to your uploaded image if different)*

### 2. Customer Risk & Churn Analysis
*Deep dive into financial risks, contract implications, and payment methods.*
![Risk Analysis Dashboard](image_ebc83d.png)
*(Note: Replace this text with the actual path to your uploaded image if different)*

## 🔍 Key Findings
Based on the diagnostic analysis, the following trends were identified:
* **High Risk Contracts:** Customers on **Month-to-Month contracts** have a churn rate of **42.7%**, compared to just 2.8% for Two-Year contracts.
* **Payment Method Impact:** Users paying via **Electronic Check** represent the highest risk group with a **53.18%** churn rate.
* **Tenure Sensitivity:** The highest churn occurs within the first **0-3 months**, indicating a critical need for better onboarding.
* **Service Loyalty:** Customers subscribing to **Tech Support** are the most loyal (lowest churn at 15%), suggesting that support services increase retention.
* **Financial Impact:** High-spending customers (high monthly charges) churn at a rate of **34%**, posing a risk to high-value revenue streams.

## 🤖 Predictive Model (Logistic Regression)
To forecast future churn, a Logistic Regression model was developed.
* **Target Variable:** Churn (1 = Yes, 0 = No)
* **Performance Accuracy:** 85%
* **Key Predictors:** Contract Type, Payment Method, Tenure, and Internet Service Type.

## 💡 Strategic Recommendations
1.  **Incentivize Long-Term Contracts:** Offer discounts or value-add services for customers switching from Month-to-Month to 1 or 2-year contracts.
2.  **Migrate Payment Methods:** Create a campaign to move Electronic Check users to Automatic Bank Transfers or Credit Cards (which have <17% churn).
3.  **Enhance Onboarding:** Implement a "First 90 Days" engagement program to reduce early-stage churn.
4.  **Bundle Tech Support:** Since Tech Support users are loyal, bundle this service with Fiber Optic packages to increase "stickiness."

## 🛠 Tools Used
* **Tableau Public:** Dashboarding, Calculated Fields, LOD Expressions, Action Filters.
* **Python (Scikit-Learn):** Data Preprocessing, Logistic Regression Modeling.
* **Excel:** Initial data inspection.

---
*This project was completed as part of the PwC Power BI/Tableau Virtual Internship on Forage.*
