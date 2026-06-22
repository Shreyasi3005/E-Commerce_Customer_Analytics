# Task 2: Predictive Modeling

## Project Title

High Value Customer Prediction using Machine Learning

---

## Objective

The objective of this task is to build a machine learning model capable of predicting whether a customer is a high-value customer based on purchasing behavior and transaction patterns.

---

## Dataset

Online Retail Dataset

The same cleaned dataset from Task 1 was used for predictive modeling.

---

## Problem Statement

Predict whether a customer belongs to the High Value Customer category using historical purchasing data.

---

## Machine Learning Workflow

### 1. Data Preparation

- Aggregated transaction-level data into customer-level data.
- Calculated:
  - Total Orders
  - Total Quantity Purchased
  - Total Revenue

### 2. Target Variable Creation

Customers were classified as:

- 1 → High Value Customer
- 0 → Normal Customer

based on median revenue.

### 3. Feature Selection

Features used:

- Total Orders
- Total Quantity

### 4. Train-Test Split

- Training Data: 80%
- Testing Data: 20%

### 5. Model Used

Random Forest Classifier

---

## Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | 87.2% |
| Precision | 87% |
| Recall | 87% |
| F1-Score | 87% |

---

## Visualizations

- Confusion Matrix
- Feature Importance Analysis

---

## Key Insights

- Customer purchase behavior is a strong indicator of customer value.
- Order frequency and quantity purchased significantly influence predictions.
- The model successfully identifies high-value customers with strong performance.
- Predictive analytics can support customer retention and targeted marketing strategies.

---

## Conclusion

A Random Forest Classifier was developed to predict high-value customers based on purchasing behavior. The model achieved an accuracy of 87.2% and demonstrated balanced performance across both customer classes.

This project showcases the practical application of machine learning in customer analytics and business decision-making.

---

## Author

**Shreyasi Rawat**
