# Churn Prediction Model Evaluation
# Business Understanding
SyriaTel, a telecommunications company, aims to predict customer churn to reduce revenue loss. The objective is to develop a binary classifier to determine whether a customer will soon discontinue their services. This model will help SyriaTel implement targeted retention strategies, such as personalized offers and improved customer service, to increase retention rates and long-term profitability. Stakeholders include internal decision-makers in marketing, customer service, and retention teams. The key question is: Can discernible patterns in the data reliably predict customer churn? The project aims to uncover actionable insights to maximize customer lifetime value and sustain business growth.

# Overview
This repository contains the evaluation results of churn prediction models based on various performance metrics.

# Key Findings
**Model Performance:**

Random Forests, Decision Trees, and KNN achieved the highest accuracy scores, all at 87%.
Logistic Regression performed slightly lower with an accuracy score of 70%.
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
