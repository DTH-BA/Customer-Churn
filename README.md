# Telecom Customer Churn Analysis

## Project Overview
With the rapid growth of the telecom industry, retaining customers has become more cost-effective than acquiring new ones.  
This project analyzes a **telecom customer dataset (3,343 rows, 11 features)** to understand **drivers of customer churn** and build a **predictive model** for churn risk.

## Objectives
- Identify key factors that drive customer churn.  
- Compare churn vs non-churn groups across important variables.  
- Build a baseline predictive model to classify customers as churn / non-churn.  
- Provide actionable insights & recommendations for Customer Service and Marketing teams.  

## Tools & Libraries
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Jupyter Notebook** for EDA, modeling
- **Tableau** for Visualization  

## Key Steps
1. **Data Overview & Cleaning**  
   - Checked missing values & outliers.  
   - Imputed missing values carefully to preserve churn patterns.  
   - Created flags for meaningful outliers (e.g., high CustServCalls).  

2. **Exploratory Data Analysis (EDA)**  
   - Compared churn vs non-churn for 4 main variables:  
     - `MonthlyCharge`  
     - `CustServCalls`  
     - `ContractRenewal`  
     - `DataPlan`  
   - Built a mini-dashboard with 4 plots to visualize churn differences.  

3. **Modeling (Predictive Analytics)**  
   - **Baseline model**: Logistic Regression for interpretability.  
   - Compared with Decision Tree / Random Forest for accuracy.  
   - Train-test split and cross-validation to evaluate models.  
   - Key metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.  

4. **Model Results**  
   - Logistic Regression: ROC-AUC ≈ *[to be filled]*  
   - Random Forest: ROC-AUC ≈ *[to be filled]*  
   - Feature importance highlighted: CustServCalls, ContractRenewal, MonthlyCharge, DataPlan.
