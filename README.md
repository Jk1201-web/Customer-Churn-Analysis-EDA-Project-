# Customer-Churn-Analysis-EDA-Project
- [Project Overview](#-project-overview)  
- [Objective](#-objective)  
- [Dataset](#-dataset)
- [Data Cleaning & Preprocessing](#-Dataset-Cleaning-&-Processing)
- [Exploratory Data Analysis(EDA)](#-Exploratory-Data-Analysis(EDA))
- [Visualizations Used](#-Visualization-used)
- [Key Insights](#-Key-Insights)
- [Tools and Technologies](#-Tools-and-Technologies)
- [Project Workflow](#-Project-Workflow)
- [Repository Structure](#-Repository-Structure)
- [Business impact](#-Business-impact)
- [Future improvement](#-Future-improvement)
## Overview
This project focuses on analyzing customer churn in the telecom/banking domain using Exploratory Data Analysis (EDA) techniques. The goal is to identify patterns, trends, and key factors that influence whether a customer leaves the service.
The analysis helps businesses make data-driven decisions to reduce customer attrition and improve retention strategies.
## Objective
- Understand customer behavior and churn patterns
- Identify key factors affecting churn
- Perform data cleaning and preprocessing
- Visualize insights using charts and graphs
- Provide actionable business insights
## Dataset
[Dataset Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
Dataset: Telco Customer Churn Dataset
Records: ~7,000+ customers
Features: 20+ columns including demographics, services, and billing
-- Key Columns:
- CustomerID
- Gender
- SeniorCitizen
- Tenure
- MonthlyCharges
- TotalCharges
- Contract
- PaymentMethod
- Churn
## Data Cleaning & Preprocessing
- Removed missing values
- Converted TotalCharges to numeric
- Handled null values after conversion
- Converted categorical fields to correct data types
- Removed unnecessary inconsistencies
## Exploratory Data Analysis (EDA)
-🔹 Churn Distribution
Identified percentage of customers who churned vs stayed
-🔹 Contract Type vs Churn
Month-to-month contracts show higher churn
-🔹 Monthly Charges Analysis
Customers with higher charges tend to churn more
-🔹 Tenure Analysis
Customers with shorter tenure are more likely to churn
🔹 Internet Service Impact
Fiber optic users show higher churn rates
-🔹 Payment Method Analysis
Electronic check users have higher churn
## Visualizations Used
- Count Plots
- Box Plots
- Heatmap (Correlation Matrix)
- Grouped Analysis
## Key Insights
-📉 Short-term customers are more likely to churn
-💰 High monthly charges increase churn probability
-📑 Month-to-month contracts are risky
-🌐 Fiber optic service users churn more
-💳 Electronic check payment users show higher churn
## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
## Project Workflow
-Data Loading
-Data Cleaning
-Data Type Conversion
-Handling Missing Values
-Exploratory Data Analysis
-Visualization
-Insight Generation
## Repository Structure
Customer-Churn-Analysis/
│
├── churn_analysis.ipynb
├── dataset.csv
├── images/
├── README.md
## Business Impact
- Helps reduce customer churn
- Improves customer retention strategies
- Supports pricing and contract decisions
- Enables targeted marketing
## Future Improvements
-Add Machine Learning model (Logistic Regression)
-Build churn prediction system
-Deploy dashboard using Power BI / Tableau
## Author
Aspiring Data Analyst
Skilled in Python, Excel, SQL, and Data Visualization
















