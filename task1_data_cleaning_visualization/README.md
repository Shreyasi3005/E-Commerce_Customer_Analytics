# E-Commerce Customer Analytics

## Project Overview

This project focuses on cleaning, preprocessing, and visualizing a real-world E-Commerce dataset to uncover meaningful business insights and customer purchasing patterns. The analysis was performed using Python and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

The objective of this project is to transform raw transactional data into actionable insights through data cleaning, exploratory data analysis (EDA), and visualization techniques.

---

## Objectives

- Understand the structure of the dataset.
- Handle missing values and duplicate records.
- Perform data cleaning and preprocessing.
- Create meaningful visualizations to analyze customer behavior.
- Identify sales trends and business patterns.
- Generate insights that can support future machine learning applications.

---

## Dataset Information

The dataset contains online retail transaction records, including:

- Invoice Number
- Product Description
- Quantity Purchased
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Kaggle Notebook

---

## Data Cleaning Process

The following preprocessing steps were performed:

- Loaded and inspected the dataset.
- Identified missing values.
- Removed records containing missing values.
- Detected and removed duplicate records.
- Converted date columns into proper datetime format.
- Created a new Revenue feature using:

**Revenue = Quantity × Unit Price**

---

## Data Visualization & Analysis

### 1. Country-wise Order Analysis
Analyzed the top countries based on the number of orders.

### 2. Top Selling Products
Identified products with the highest sales volume.

### 3. Monthly Revenue Trend
Studied revenue fluctuations throughout the year and identified seasonal patterns.

### 4. Revenue Distribution
Analyzed how revenue is distributed across transactions.

### 5. Correlation Heatmap
Examined relationships between Quantity, Unit Price, and Revenue.

### 6. Outlier Detection
Detected unusual purchase quantities using box plots.

---

## Key Insights

- The United Kingdom generated the highest number of orders and dominates the customer base.
- A small group of products contributes significantly to total sales volume.
- Revenue shows strong growth during the final quarter of the year.
- November recorded the highest revenue, indicating seasonal shopping behavior.
- Most transactions generate relatively low revenue, while a few transactions contribute exceptionally high revenue.
- Significant outliers exist in purchase quantities, suggesting bulk purchasing activity.
- Quantity and Revenue exhibit a positive relationship.

---

## Conclusion

The dataset was successfully cleaned and analyzed to extract valuable business insights. Through data visualization and exploratory analysis, important patterns related to customer behavior, product demand, and revenue trends were identified.

This project serves as a strong foundation for future machine learning applications such as sales forecasting, customer segmentation, recommendation systems, and predictive analytics.

---

## Future Scope

- Customer Segmentation
- Sales Forecasting
- Product Recommendation System
- Customer Purchase Prediction
- Business Intelligence Dashboard

---

## Author

**Shreyasi Rawat**
