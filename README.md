# Retail-Sales-Prediction
This is a Supervised ML Project which has made use of regression models to make predictions from the given data set.

# Project Summary 
The Retail Sales prediction capstone project is provided with two CSV files that is Rossmann Stores Data and Store that consists of 19 variables which contains different kinds of information.

A) Initially, data cleaning and wrangling were conducted to combine two datasets. Then, the Exploratory Data Analysis (EDA) was performed by creating various visualization charts to analyze the data. During the EDA, some interesting findings were discovered such as the high correlation between sales and customers, more sales on Mondays due to store closures on Sundays, promotions leading to more sales, stores staying open more frequently during school holidays and generating more sales compared to state holidays, store type 'a' having the highest sales on average, Assortment level-b (i.e., 'extra') resulting in the highest average sales, school holidays affecting only 17.9% of sales, and so on.

B) In the second step we did hypothesis testing:

1. Hypothesis: Stores located closer to competition have significantly lower sales than stores located further away

2. Null hypothesis: There is no significant difference in sales between stores closer to the competition and farther away.

3. Alternative hypothesis: Stores closer to competition have significantly lower sales than stores farther away.

To test this hypothesis, we performed a two-sample t-test between the sales of stores located within 10 km of competition and
stores located further away. We can set a significance level of 0.05

C) In the third step we performed feature engineering like filling missing values, handling null values, handling columns, deleting unnecessary columns, feature processing, feature extracting, outliers handling and feature selection.

D) The last but not the least step, of our project is "model deployment". We have deployed two models, first one is the "linear regression model" and the second one is the "lasso regression model".

# Conclusion of both the models:

The evaluation of regression models often uses two metrics: MSE and R2 score. Both Linear Regression and Lasso Regression models have similar performance, with Linear Regression slightly outperforming Lasso Regression in terms of MSE and R2 score. MSE is a measure of the average difference between predicted and actual values, where lower MSE implies better performance. R2 score measures how much of the dependent variable's variance can be explained by independent variables and a higher R2 score indicates a better fit of the linear regression model.

# Problem Statement

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.
