# Customer Churn Prediction for XYZ Multistate Bank

## Project Overview
This project analyzes customer churn for XYZ Multistate Bank using a dataset that captures key customer attributes and behaviors. The goal is to identify factors influencing churn and build a predictive model to help the bank retain customers.

## Dataset Overview
The dataset consists of 18 features and one target variable (`Exited`), which indicates whether a customer left the bank (`1`) or remained (`0`). The features are grouped into relevant categories:

- **Demographic Information:** `Geography`, `Gender`, `Age`
- **Customer Relationship with Bank:** `Tenure`, `NumOfProducts`, `IsActiveMember`
- **Financial Information:** `CreditScore`, `Balance`, `EstimatedSalary`
- **Banking Behavior:** `HasCrCard`, `CardType`, `PointsEarned`
- **Customer Feedback & Satisfaction:** `Complain`, `Satisfaction Score`
- **Target Variable:** `Exited`

## Exploratory Data Analysis (EDA)
To understand customer behavior and its relationship with churn, we performed:
- **Feature Distribution Analysis**: Identified patterns in credit scores, age, tenure, and balance.
- **Correlation Analysis**: Determined relationships between independent features and churn.
- **Churn Trends**: Observed how different factors impact churn rates.

## Machine Learning Model
We implemented **Logistic Regression** as the primary model to predict customer churn. Steps included:

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Feature Selection**: Retained the most relevant features based on statistical significance.
3. **Model Training & Evaluation**: The model achieved an accuracy of **99.85%**, indicating high predictive power.

### Model Performance Metrics:
- **Accuracy**: 0.9985
- **Precision, Recall, F1-score**: Evaluated for better interpretability.
- **Confusion Matrix**: Analyzed false positives and false negatives.

## Key Insights & Business Impact
- **High Credit Score & Balance Customers**: Less likely to churn, requiring minimal retention efforts.
- **Inactive Members**: Higher churn risk, suggesting the need for engagement strategies.
- **Customers with Fewer Products**: More prone to churn, highlighting cross-selling opportunities.
- **Complaint Trends**: Customers who filed complaints had higher churn rates, stressing the need for service improvements.

## Conclusion
This project provides a data-driven approach to predicting customer churn and offers actionable insights for XYZ Multistate Bank. By targeting at-risk customers with personalized retention strategies, the bank can enhance customer satisfaction and reduce churn.

## Future Work
- Implement advanced models like Random Forest or XGBoost for better predictive performance.
- Develop a real-time churn prediction system integrated with bank operations.
- Conduct A/B testing to evaluate retention strategies based on model insights.

---
### Author: Omar  
**Tools Used:** Python, Pandas, Seaborn, Scikit-Learn

Feel free to contribute or raise issues in this repository!
