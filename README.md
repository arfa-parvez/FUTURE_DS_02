# FUTURE_DS_02
TELO_CUSTOMER_CHURN_ANALYSIS

 SaaS Subscription Churn Analysis (Telco Dataset)

 Project Overview

Customer churn is one of the biggest challenges in subscription-based businesses (SaaS / Telecom).

This project analyzes the **Telco Customer Churn Dataset** to:

* Understand customer behavior
* Identify churn patterns
* Estimate customer lifetime value (LTV)
* Build insights using Python & Power BI

 Dataset

* **Source:** Kaggle
* **Dataset Name:** Telco Customer Churn
* **File Used:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
* **Records:** 7,043 customers
* **Target Variable:** `Churn` (Yes / No)


 Tools Used

 Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

 Power BI
* Data Modeling
* DAX
* Interactive Dashboards


 Project Workflow

 Data Cleaning (Python)

* Removed unnecessary columns (CustomerID)
* Converted `TotalCharges` to numeric
* Handled missing values
* Converted categorical variables
* Fixed tenure datatype issues



 Feature Engineering

 Tenure Groups

Customers were grouped based on subscription duration:

| Tenure (Months) | Group     |
| --------------- | --------- |
| 0–12            | 0–1 year  |
| 12–24           | 1–2 years |
| 24–48           | 2–4 years |
| 48–72           | 4–6 years |


 Estimated Lifetime Value (LTV)
Estimated using:
Estimated_LTV = MonthlyCharges × Tenure



Exploratory Data Analysis (EDA)

Performed analysis on:

* Churn distribution
* Contract type vs churn
* Internet service vs churn
* Monthly charges comparison
* Tenure impact on churn
* Estimated LTV comparison


Key Insights
 Insight:
Customers who stay generate significantly higher lifetime value.

This means retaining customers is more profitable than acquiring new ones.


 Major Churn Drivers

* Month-to-month contracts
* High monthly charges
* Low tenure (new customers)
* Electronic check payment method


 Power BI Dashboard

Power BI dashboard includes:

* Churn rate KPI
* LTV comparison
* Contract type impact
* Tenure distribution
* Monthly charges analysis
* Interactive slicers


 Business Impact
This project helps businesses:
* Reduce churn rate
* Identify high-risk customers
* Increase customer retention
* Improve marketing targeting
* Maximize customer lifetime value



