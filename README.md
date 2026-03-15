# Customer Churn Prediction using Machine Learning

This project predicts customer churn using machine learning techniques. The goal is to identify customers who are likely to stop using a service and help businesses take proactive retention actions.

---

## Project Objective

- Analyze customer behavior data
- Identify factors contributing to churn
- Build machine learning models to predict churn
- Provide insights for improving customer retention

---

## Dataset

The dataset used in this project contains customer information, including:

- Customer demographics
- Account details
- Service usage
- Billing information
- Churn status (Target Variable)

Dataset file:

Each row represents a customer record and includes multiple features that influence churn behavior.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Exploratory Data Analysis (EDA)

EDA was performed to understand the patterns in customer churn.

Key analysis included:

- Distribution of churn vs non-churn customers
- Correlation between features
- Impact of contract type on churn
- Monthly charges vs churn relationship

### Example Visualizations

Churn Distribution

![Churn Distribution](images/churn_distribution.png)

Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

---

## Machine Learning Models

The following models were used for churn prediction:

- Logistic Regression
- Random Forest
- Decision Tree

Model training steps:

1. Data preprocessing
2. Feature encoding
3. Train-test split
4. Model training
5. Performance evaluation

---

## Results

The Random Forest model achieved the best performance.

Example metrics:

Accuracy: **87%**

Key insights:

- Customers with month-to-month contracts churn more frequently
- Higher monthly charges increase churn probability
- Long-term contract customers have lower churn rates

---

## Feature Importance

Top features influencing churn:

- Contract type
- Monthly charges
- Tenure
- Payment method

![Feature Importance](images/feature_importance.png)

---


---

## Project Author

Akshat Sharma  
Data Analyst | Python | Machine Learning | SQL

GitHub: https://github.com/AakshatSharma7  
LinkedIn: https://www.linkedin.com/in/akshat-sharma-45b314276
