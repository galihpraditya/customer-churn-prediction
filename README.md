# Customer Churn Prediction

This project aims to predict customer churn using various machine learning models. The dataset contains customer information from a telecommunications company. The goal is to build and evaluate models to identify which customers are likely to leave the service. The dataset can be accessed from the following link: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Introduction
Customer churn prediction is a critical task for businesses aiming to retain their customers. By identifying customers at risk of leaving, companies can implement targeted retention strategies.

## Dataset
The dataset includes features such as:
- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

## Modeling
The following machine learning models were implemented:
1. **K-Nearest Neighbors (KNN)**
2. **Random Forest Classifier**
3. **Decision Tree Classifier**
4. **AdaBoost Classifier**

## Results
| Model               | Accuracy |
|---------------------|----------|
| KNN                 | 75.17%   |
| Random Forest       | 78.86%   |
| Decision Tree       | 72.46%   |
| AdaBoost Classifier | 81.04%   |

## Conclusion
The AdaBoost Classifier provided the best performance in predicting customer churn. The project highlights the importance of feature engineering, proper model selection, and evaluation.

## Future Improvements
- Perform hyperparameter tuning for better model performance.
- Handle missing values using imputation techniques instead of dropping rows.
- Add more advanced visualizations in the EDA.
- Explore additional machine learning models.
