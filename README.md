# Telco Customer Churn Analysis Predictive Modelling
This project develops a machine learning model to predict customer churn and factors from Telco Company customers.
The goal is to find and plan marketing strategies to prevent customer churn and improving customer lifetime values.

#### Business Objectives:
Implementing a better marketing campaign for targeted customer, and improving products and services quality to increased customer loyalty.

## 2. Data Sources
- data_telco_customer_churn.csv

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy, SciPy)
- Machine Learning: scikit-learn, LightGBM
- Visualization: Matplotlib, Seaborn
- Version Control: GitHub
- Development Environment: Jupyter Notebook, Visual Studio Code

## 4. Project Structure

```
├── README.md                      <- Project documentation (you are here)
│
├── data
│   ├── data_telco_customer_churn.csv  <- Internal Sources
│
├── models/                       <- Serialized machine learning models (.pkl)
│
├── notebooks
│   ├── main.ipynb
│

```

## 5. Summary of Finding
### 5.1 Business Insight
- The model shows that churn mostly comes from month to month customers, new customers with short tenure, high-paying users, and people who don’t use add on services. These groups are the main targets for retention.
- Since contract type, tenure, and monthly charges strongly influence churn, PT Telco can reduce churn by promoting long term contracts, improving early onboarding, and offering flexible or better value pricing for sensitive users.
- Add-on services help customers stay longer, so promoting bundled services can increase loyalty. With LightGBM, PT Telco can identify at risk customers early and focus retention efforts more efficiently.

### 5.2 Actionable Recommendation
- PT Telco should focus on month to month customers by offering contract upgrades, discounts, or bundled deals, and also strengthen early onboarding for new customers with short tenure to prevent them from leaving too quickly.
- Since high monthly charges increase churn, the company should improve its pricing strategy with flexible plans, usage-based options, or targeted discounts for high paying customers.
- Add-on services help reduce churn, so PT Telco should promote service bundles and free trials, and use the LightGBM model as an early warning system to target retention efforts more efficiently and reduce unnecessary marketing costs.
