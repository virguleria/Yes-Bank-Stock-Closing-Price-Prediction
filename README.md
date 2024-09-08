Yes Bank Stock Closing Price Prediction
Project Overview
This project aims to predict Yes Bank's monthly stock closing price using historical stock price data, including open, high, low, and closing prices, with a focus on analyzing the impact of the 2018 Rana Kapoor fraud case. The project applies time series analysis and machine learning models to understand stock price trends and forecast future prices.

Project Type
Regression
Contribution
Individual Project
Objective
Yes Bank is a prominent financial institution in India, and it experienced significant volatility in its stock prices due to the Rana Kapoor fraud case in 2018. The primary goal of this project is to develop machine learning models that accurately predict the monthly closing price of Yes Bank's stock, considering historical trends and significant events like the 2018 fraud case.

Dataset
The dataset consists of monthly stock prices for Yes Bank, including:

Open Price: The stock price at the start of the month
High Price: The highest stock price during the month
Low Price: The lowest stock price during the month
Close Price: The stock price at the end of the month (Target Variable)
Steps Involved
1. Import Libraries
Imported necessary Python libraries for data analysis, visualization, and machine learning.
2. Understanding Variables
Explored and described each variable in the dataset to understand its relevance to the project goal.
3. Data Wrangling
Performed data cleaning tasks such as handling missing values, duplicates, and outliers.
Applied log transformations to positively skewed variables for normalization.
4. Data Visualization & Storytelling
Visualized the relationship between variables using scatter plots, histograms, and line charts.
Analyzed the impact of the 2018 fraud case, showing a sharp decline in stock prices.
5. Feature Engineering & Data Pre-processing
Created additional features such as the mean of open, high, and low prices.
Generated lag features to capture temporal patterns in stock prices.
Addressed multicollinearity by using Variance Inflation Factor (VIF).
6. Machine Learning Model Implementation
Model 1: Ridge Regression
Ridge regression was implemented to reduce overfitting by adding regularization.
Model 2: Random Forest
A Random Forest model was also developed to capture non-linear relationships and handle complex data structures.
7. Model Evaluation
Both models were evaluated for their predictive accuracy using performance metrics such as RMSE, MAE, and R-squared.
8. Conclusion
The Random Forest model performed well, capturing temporal trends and handling new features.
The fraud case in 2018 showed a clear impact on the stock's closing price, which was reflected in the model's predictions.
The models showed strong performance and can be used for future predictive tasks with additional data.
Results
The Ridge Regression and Random Forest models were able to predict Yes Bank's monthly closing stock prices with high accuracy.
Feature engineering helped to capture important trends, and the fraud case in 2018 was handled effectively by the models.
The models can be further optimized and deployed for real-world applications in stock price prediction.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Statsmodels
