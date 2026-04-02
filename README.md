# Customer Churn Analysis
## *Exploratory Data Analysis (EDA)*
- [Project Overview](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-?tab=readme-ov-file#overview)  
- [Objective](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#objective)  
- [Dataset](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#dataset)
- [How to Run the Project](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-/blob/main/README.md#how-to-run-the-project)
  - [churn_analysis.ipynb](churn_analysis.ipynb)
- [Data Cleaning & Preprocessing](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#data-cleaning--preprocessing)
- [Exploratory Data Analysis(EDA)](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#exploratory-data-analysis-eda)
- [Visualizations Used](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#visualizations-used)
- [Key Insights](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#key-insights)
- [Tools and Technologies](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#tools--technologies)
- [Project Workflow](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#project-workflow)
- [Business impact](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#business-impact)
- [Future improvement](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#future-improvements)
- [Connect with me](https://github.com/Jk1201-web/Customer-Churn-Analysis-EDA-Project-#connect-with-me)
   - [Linkdin](www.linkedin.com/in/jijau-khandale)
   - [GitHub](https://github.com/Jk1201-web)
   - [Kaggle](https://www.kaggle.com/jijaumohankhandale)
     
## Overview
- This project analyzes customer churn data using Python to identify key factors influencing customer attrition and retention.
- The goal is to help businesses understand why customers leave, identify high-risk segments, and implement strategies to improve customer retention.
  
## Objective
1. Analyze overall churn rate
2. Identify key factors influencing churn
3. Evaluate impact of contract type on churn
4. Perform exploratory data analysis (EDA)
5. Generate actionable business insights
   
## Dataset
[https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Dataset: Telco Customer Churn Dataset
- Records: ~7,000+ customers
- Features: 20+ columns including demographics, services, and billing
  
### Key Columns:
- CustomerID
- Gender
- SeniorCitizen
- Tenure
- MonthlyCharges
- TotalCharges
- Contract
- PaymentMethod
- Churn
  
## Business Problems Solved
1. What is the overall churn rate?
2. How many customers are leaving the business?
3. Which customer segments have the highest churn?
4. How does contract type affect churn?
5. What strategies can reduce churn?
   
## Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
## Analysis Performed
1. Data Cleaning & Preparation
2. Exploratory Data Analysis (EDA)
3. Churn Distribution Analysis
4. Contract-wise Churn Analysis
5. Data Visualization
   
## Key Metrics
| Metric	| Value |
|------|------|
| Total Customers |	7,032 |
| Customers Retained	| 5,163 |
| Customers Churned |	1,869 |
| Churn Rate | 26.58% |

### Detailed Analysis
1. Overall Churn Distribution
   
| Churn Status | Count | Percentage |
|------|------|------|
| No |	5,163 |	73.42% |
| Yes	| 1,869	| 26.58% |

   - Approximately 26.6% of customers have churned, indicating a high attrition rate Nearly 1 out of 4 customers leaves the business

2. Churn by Contract Type
| Contract Type |	Retained (No) |	Churned (Yes) |
| Month-to-month |	57.29%	| 42.71% |
| One year | 88.72%	| 11.28% |
| Two year |	97.15% |	2.85% |

   - Month-to-month customers show the highest churn (~43%)
   - One-year contracts significantly reduce churn (~11%)
   - Two-year contracts have minimal churn (~3%)
   - Customer commitment directly impacts retention
     
## Key Insights Summary
- Overall churn rate is ~26.6% (high risk)
- Majority of churn comes from month-to-month customers
- Long-term contracts drastically reduce churn
- Customer retention improves with commitment-based plans
  
## Business Recommendations
1. Offer incentives for long-term subscriptions
2. Target month-to-month customers with retention campaigns
3. Provide discounts for contract upgrades
4. Monitor high-risk customer segments proactively
   
## How to Run the Project
- Install required libraries:
```pip install pandas matplotlib seaborn```
- Load dataset in Python
- Run analysis script / notebook
   [churn_analysis.ipynb](churn_analysis.ipynb)
- View outputs and visualizations
  
## Project Workflow
1. Data Collection
2. Data Cleaning
3. Data Exploration (EDA)
4. Data Visualization
5. Insight Generation
6. Business Recommendations
   
## Project Structure
Customer-Churn-Analysis/
 ┣ Dataset/
 ┃ ┗ churn_data.csv
 ┣ Notebook/
 ┃ ┗ churn_analysis.ipynb
 ┣ Images/
 ┃ ┗ charts.png
 ┗ README.md
 
## ## Connect With Me
 - [LinkedIn](www.linkedin.com/in/jijau-khandale)
 - [GitHub](https://github.com/Jk1201-web)
 - [Kaggle](https://www.kaggle.com/jijaumohankhandale)

*If you found this project useful, consider giving it a star!*

















