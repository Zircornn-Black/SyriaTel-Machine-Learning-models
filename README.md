# Churn Prediction Model Evaluation
# Business Understanding
SyriaTel, a telecommunications company, aims to predict customer churn to reduce revenue loss. The objective is to develop a binary classifier to determine whether a customer will soon discontinue their services. This model will help SyriaTel implement targeted retention strategies, such as personalized offers and improved customer service, to increase retention rates and long-term profitability. Stakeholders include internal decision-makers in marketing, customer service, and retention teams. The key question is: Can discernible patterns in the data reliably predict customer churn? The project aims to uncover actionable insights to maximize customer lifetime value and sustain business growth.

# Overview
This repository contains the evaluation results of churn prediction models based on various performance metrics.
Churn distribution eveluated where out of 3,333 customers in the dataset, 483 have terminated their contract with SyriaTel, representing 14.5% of customers lost.
![image](https://github.com/Zircornn-Black/SyriaTel-Machine-Learning-models/assets/158102409/c1137f18-793a-49de-a130-93a4a56ff5ac)
The Key features in our data are as per below.
![image](https://github.com/Zircornn-Black/SyriaTel-Machine-Learning-models/assets/158102409/3887beac-82e1-497c-befd-b56fb526bf25)

# Key Findings
**Model Performance:**
The area under the curve below using ROC Curve analysis showed that logistic regression was the best but after more models evaluation, we saw that Random Forests, Decision Trees, and KNN achieved the highest accuracy scores, all at 87%.
Logistic Regression performed slightly lower with an accuracy score of 70%.
![image](https://github.com/Zircornn-Black/SyriaTel-Machine-Learning-models/assets/158102409/65c6409d-d43e-4b15-832c-f07098e1d91e)

**F1 Scores:**

Random Forests outperformed other models with an F1 score of 0.55, indicating better precision and recall.
Decision Trees had a lower F1 score of 0.42.
**Feature Importance:**

According to Decision Trees, the most important features for predicting churn are customer service calls and total international calls.
**Odds Ratios:**

Customers with an International Plan are 7 times more likely to churn compared to those without.
Each additional customer service call increases the likelihood of churn by a factor of 1.55.
**Best Model**:

Random Forests emerged as the best model due to its high accuracy and F1 score.
# Conclusion
Based on the evaluation results, Random Forests offer the most promising approach for churn prediction due to their superior performance in accuracy and F1 score compared to other models.
