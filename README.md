# customer-churn-retention-intelligence
End-to-end customer churn analytics project using SQL, Python, and Power BI to identify churn drivers, analyze customer behavior, evaluate revenue impact, and recommend data-driven retention strategies.

Project Overview
Customer churn is a major challenge for subscription-based businesses. This project analyzes customer demographics, service usage, billing patterns, and contract information to identify the factors influencing customer churn. Using SQL, Python, and Power BI, the project delivers actionable insights and retention strategies to reduce customer attrition.


Business Problem
The telecom company is experiencing customer attrition, impacting long-term revenue and customer lifetime value. The objective is to identify the primary drivers of churn and recommend data-driven retention strategies.


Objectives
- Analyze customer churn patterns.
- Identify high-risk customer segments.
- Evaluate revenue impact due to churn.
- Compare churn across contracts, payment methods, and internet services.
- Build an interactive Power BI dashboard for business stakeholders.

  
Tools Used
- SQL (SQLite)
- Python (Pandas, Matplotlib)
- Power BI
- Google Colab

  
Dataset
- IBM Telco Customer Churn Dataset
- 7,032 customers
- 21 attributes

  
Data Cleaning
- Converted TotalCharges to numeric format.
- Removed records with missing TotalCharges values.
- Verified duplicates and missing values.

  
SQL Analysis
Performed SQL analysis to answer business questions including:

- Overall churn rate
- Revenue lost due to churn
- Churn by contract
- Churn by payment method
- Churn by internet service
- High-value churned customers

Python Analysis
Performed exploratory data analysis using Python:

- Customer churn distribution
- Contract distribution
- Internet service distribution
- Monthly charges distribution
- Customer tenure distribution
  
Power BI Dashboard
The dashboard consists of four interactive pages:

- Executive Overview
- Customer Insights
- Revenue & Billing Analysis
- Retention Strategy

(Add your dashboard screenshots below this section.)

Key Insights


- Customers with month-to-month contracts showed the highest churn.
- Electronic check users experienced higher churn compared to other payment methods.
- Fiber optic customers contributed significantly to churn.
- High-value customers leaving the company resulted in substantial revenue loss.

  Business Recommendations

- Encourage customers to switch to long-term contracts.
- Provide targeted retention offers to high-value customers.
- Improve service quality for high-churn customer segments.
- Offer personalized pricing and loyalty programs.
Repository Structure
