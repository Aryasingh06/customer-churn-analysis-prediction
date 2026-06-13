# 📊 Customer Churn Analysis & Prediction

## Project Overview
Customer churn is one of the most important business challenges in the telecom industry. Retaining existing customers is often more cost-effective than acquiring new ones. This project analyzes customer churn behavior using SQL, Python, and Machine Learning to identify key churn drivers and predict customers who are likely to leave.
The project combines business analysis with predictive modeling to generate actionable insights for customer retention strategies.

## Objectives
- Analyze customer churn patterns using SQL and Python.
- Identify factors influencing customer attrition.
- Perform feature engineering to improve analysis.
- Build a Machine Learning model for churn prediction.
- Provide business recommendations based on data-driven insights.

##  Dataset

IBM Telco Customer Churn Dataset
The dataset contains information about:
- Customer demographics
- Service subscriptions
- Internet services
- Contract types
- Payment methods
- Monthly and total charges
- Customer churn status

##  Technologies Used
- Python
- SQL (SQLite)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
###  Data Cleaning
- Removed inconsistencies and handled missing values.
- Converted data types for analysis.
- Prepared data for SQL and Machine Learning workflows.

### . SQL Analysis
Performed business-focused SQL queries to analyze:
- Total customers
- Churned customers
- Churn rate
- Contract-wise churn
- Payment method churn
- High-risk customers
- Customer segments

###  Feature Engineering
Created additional features:
- **CustomerType** (New / Loyal)
- **ChargeCategory** (Low / Medium / High)
- **AvgSpendPerMonth**

### Exploratory Data Analysis (EDA)
Visualized customer behavior and churn patterns using:
- Churn Distribution
- Contract Type vs Churn
- Monthly Charges vs Churn
- Tenure Distribution
- Payment Method vs Churn
- Customer Type vs Churn
- Correlation Heatmap

###  Machine Learning
Implemented a Logistic Regression model for churn prediction.
Steps included:
- Target variable encoding
- Categorical feature encoding
- Feature scaling
- Train-test split
- Model training
- Prediction and evaluation
- Feature importance analysis

##  Model Performance

Alorithm: Logistic Regression
### Evaluation Metrics
- Accuracy: 81.6%
- Confusion Matrix
- Precision
- Recall
- F1-Score
The model achieved strong performance in identifying customer churn behavior and provided interpretable feature importance for business decision-making.

## Key Business Insights
- Overall churn rate is approximately 26.5%
- Customers with month-to-month contracts have the highest churn rate.
- Customers with higher monthly charges are more likely to leave.
- New customers show significantly higher churn behavior.
- Customers using electronic check payments have elevated churn rates.
- Longer customer tenure is strongly associated with customer retention.
- Internet service type and support-related services influence churn behavior.

## Business Recommendations
- Encourage customers to switch to long-term contracts.
- Provide loyalty rewards for long-term customers.
- Improve onboarding programs for new customers.
- Review pricing strategies for high-charge customers.
- Develop retention campaigns for high-risk customer segments.
- Improve support services to strengthen customer satisfaction.

##  Project Visualizations
### Churn Distribution
![Churn Distribution](screenshots/churn_distribution.png)

### Contract Type vs Churn
![Contract Type vs Churn](screenshots/contract_type_vs_churn.png)

### Monthly Charges vs Churn
![Monthly Charges vs Churn](screenshots/monthlycharges_vs_churn.png)

### Customer Type vs Churn
![Customer Type vs Churn](screenshots/customer_type_vs_churn.png)

### Correlation Heatmap
![Correlation Heatmap](screenshots/correlation_heatmap.png)

### Confusion Matrix
![Confusion Matrix](screenshots/confusion_matrix.png)

##  Future Improvements
- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Power BI Dashboard
- Streamlit Web Application Deployment
- Customer Retention Recommendation System

## Conclusion

This project demonstrates an end-to-end Data Analytics and Machine Learning workflow, covering data cleaning, SQL analysis, feature engineering, visualization, and predictive modeling. The analysis identifies key churn drivers, while the machine learning model helps predict customer attrition, enabling businesses to take proactive retention measures.
