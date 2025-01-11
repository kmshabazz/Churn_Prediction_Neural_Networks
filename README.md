# Churn_Prediction_Neural_Networks
Analyze the customer data, build a neural network to help the operations team identify the customers that are more likely to churn, and provide recommendations on how to retain such customers
# Skills & Tools Covered
EDA, Data Preprocessing, Tensorflow, Keras, Artificial Neural Networks, Regularization
# Background
In the banking industry, one of the significant challenges is customer churn, where customers leave for a competitor. Customer churn poses a risk to long-term profitability, as the cost of acquiring new customers typically exceeds the cost of retaining existing ones.
# Business Problem
To reduce churn, banks need to proactively identify which customers are at risk of leaving, allowing management to take targeted actions to improve service and retain valuable clients. Understanding the factors driving customer decisions is key to improving overall customer satisfaction and loyalty.
# Solution
To build a neural network-based classifier capable of predicting whether a given bank customer will churn.
# Data Overview
Dataset Shape: 10000 rows containing 14 columns of data
<br> Datatypes in dataset: floats, integers, objects
<br>  Statistical Summary:
<br>  Credit Score: The average credit score is 650, ranging from 350 to 850, indicating a wide
variation in customer credit histories.
<br>  Age: The mean age is 39, with customers ranging from 18 to 92, highlighting a diverse age
demographic.
<br>  Balance: Many customers have zero balance, but account balances can reach as high as
250,898, with an average of 76,486.
<br> Churn Rate: Approximately 20% of customers have exited the bank, indicating a significant
churn rate.
<br> Product Ownership: Customers typically have 1 to 4 products, with an average of 1.53
products per customer.
# Final Model Selection
For the final model, I would choose Model 5 (Neural Network with SMOTE, Adam Optimizer, and Dropout) since it achieved the best recall of 1.0 on both the training and validation sets. The model effectively addresses the class imbalance and correctly identifies all instances of the '1' for exited customers
<br> Business Relevance:
<br> Proactively Address Churn: By identifying at-risk customers, the business can focus on retention strategies like loyalty programs, improving customer satisfaction, or offering discounts.
<br> Improve Revenue Stability: By reducing customer churn, the company can maintain a stable revenue stream and avoid the negative financial impacts associated with losing customers.
<br> Optimize Retention Resources: The business can direct resources toward customers who are likely to churn, improving the efficiency of retention campaigns.
# Project Final File:
[Kalifa Shabazz_Neural Networks Final Project_October 2024.pptx.pdf](https://github.com/user-attachments/files/18386751/Kalifa.Shabazz_Neural.Networks.Final.Project_October.2024.pptx.pdf)
