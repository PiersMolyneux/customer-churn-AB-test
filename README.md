# customer-churn-AB-test
## Project Overview
This project aims to identify at-risk customers in an e-commerce context to implement targeted retention strategies effectively. By analyzing customer behavior, transaction history, and engagement metrics, we predict which customers are likely to churn. This enables proactive engagement to improve customer retention rates.
We first compare various machine learning methods at predicting how likely a customer is to churn. We find out the best model is the random forest.

Once at-risk customers have been identified, we aim to create a mock AB Testing Campaign, simulating a real one. This targeted campaign aims to reduce the churn of these at-risk customers. This campaign involves a personalised apology with cashback incentive for complaints of customers with a tenure < 1. We perform a Pearson's Chi-squared test, using hypothetical results, and conclude that our campaign is not statistically significant, hence has not worked.

## Dataset Description
The E-commerce Customer Churn Analysis and Prediction Dataset contains over 5000 rows and 20 columns, detailing customer demographics, online behavior, and churn status. Key features include customer age, gender, purchase history, website activity, and customer service interactions.

## Modules Utilised
This notebook utilises pandas for dataset operations, seaborn + matplotlib for visualisations, and SkLearn for machine learning applications.
