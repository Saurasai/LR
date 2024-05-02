# Unveiling Customer Behavior: A Linear Regression Approach to Ecommerce Data

## Overview
This project involves the analysis of customer data for an Ecommerce company based in New York City. The company offers clothing online sales and in-store style and clothing advice sessions. Customers can access these services through a mobile app or website.

## Objective
The main goal of this analysis is to assist the Ecommerce company in determining whether to prioritize improving the mobile app experience or the website. By analyzing customer data, including their session behavior, purchase history, and other relevant factors, we aim to provide insights that will guide the company's decision-making process.

## Dataset
The dataset used for this analysis is named "Ecommerce Customers". It contains anonymized information about customers, including their email addresses, addresses, avatars, average session length, time spent on the app and website, length of membership, and yearly amount spent.

## Methodology
The analysis involves several steps:

1. Exploratory Data Analysis (EDA):
   - Descriptive statistics are computed using `describe()` to understand the distribution of numerical features.
   - The `info()` method provides insights into the dataset's structure and data types.
   - Data visualization using `matplotlib` and `seaborn` libraries to explore relationships between variables.
  
2. Linear Regression:
   - Linear regression models are used to predict the yearly amount spent by customers based on various features.
   - The model is trained on a subset of the data using the `train_test_split` method from `sklearn.model_selection`.
   - The model's coefficients are computed to understand the relationships between predictor variables and the target variable.
   - Predictions are made on the test data, and performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) are calculated using `sklearn.metrics`.

## Key Findings
Based on the linear regression analysis, the following key findings have been identified:
- Customers who spend more time on the app tend to spend more annually compared to those who spend more time on the website.
- Length of membership is strongly positively correlated with yearly amount spent.
- The coefficients of the linear regression model indicate the impact of each predictor variable on the yearly amount spent.

## Conclusion
This analysis provides valuable insights into customer behavior and preferences for the Ecommerce company. Based on the findings, the company can make informed decisions about prioritizing improvements to the mobile app or website to enhance the overall customer experience and drive business growth.

