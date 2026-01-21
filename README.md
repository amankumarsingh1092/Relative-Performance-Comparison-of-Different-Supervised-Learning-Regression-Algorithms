# NTCC Dissertation
# Relative-Performance-Comparison-of-Different-Supervised-Learning-Regression-Algorithms
<img width="1536" height="1024" alt="ChatGPT Image Jan 21, 2026, 09_18_06 PM" src="https://github.com/user-attachments/assets/bedfeac8-5eb6-4495-bf04-0c244dd50a09" />

## Stock Market Price Prediction and Volatility Forecasting using Machine Learning and Time-Series Models
## Project Overview

This project presents a comprehensive empirical analysis of stock price prediction and volatility forecasting for major Indian equities using supervised learning regression models and classical time-series techniques.
The study utilizes historical data from the Bombay Stock Exchange (BSE) and National Stock Exchange (NSE) covering the period 1 April 2020 to 31 March 2025.

The objective is to compare the predictive performance of various machine learning models with traditional econometric approaches such as ARIMA, SARIMA, and GARCH, and to develop an integrated framework for price forecasting and risk analysis.

## Objectives
* To evaluate and compare supervised learning regression models for stock price prediction
* To analyze the impact of seasonality using ARIMA and SARIMA models
* To model and forecast stock return volatility using GARCH models
* To compare predictive performance across BSE and NSE
* To provide an integrated framework combining price forecasting and volatility modeling

## Companies Analyzed

The study focuses on four large-cap Indian companies representing key economic sectors:
* Reliance Industries Ltd. (Energy)
* HDFC Bank Ltd. (Banking)
* Infosys Ltd. (Information Technology)
* Tata Consultancy Services (TCS) (Information Technology)

Models Implemented
## Supervised Learning Regression Models
* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest Regression
* Gradient Boosting Regression
* Support Vector Regression (SVR)
* k-Nearest Neighbors (KNN)
* Artificial Neural Networks (ANN)

## Time-Series Models
* ARIMA (Autoregressive Integrated Moving Average)
* SARIMA (Seasonal ARIMA)

## Volatility Models
* ARCH
* GARCH (1,1)

## Evaluation Metrics
Model performance is evaluated using:
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Coefficient of Determination (R²)
* Akaike Information Criterion (AIC)
* Bayesian Information Criterion (BIC)

## Dataset Description
* Source:
  * Bombay Stock Exchange (BSE): https://www.bseindia.com
  * National Stock Exchange (NSE): https://www.nseindia.com
* Time Period: 01-04-2020 to 31-03-2025
* Frequency: Daily
* Data Fields: Open, High, Low, Close, Volume

## Tools & Technologies
* Programming Language: Python
* Libraries: NumPy, Pandas, Scikit-learn, Statsmodels, ARCH
* Visualization: Matplotlib, Seaborn
* Environment: Jupyter Notebook

## Key Findings
* Linear and regularized regression models (Linear, Ridge, Lasso) consistently achieved strong predictive performance.
* SARIMA models outperformed ARIMA models across all companies and exchanges, highlighting the importance of seasonality.
* GARCH(1,1) models effectively captured volatility clustering in stock returns.
* Minimal performance differences were observed between BSE and NSE, indicating high informational efficiency.
* An integrated SARIMA–GARCH framework provides a robust approach for price and risk forecasting.

## Research Contribution
This project demonstrates that:
* Simpler and interpretable models can outperform complex machine learning models in structured financial time series.
* Seasonal and volatility-aware modeling significantly improves forecasting reliability.
* Hybrid modeling approaches are well-suited for financial analytics in emerging markets like India.

## References
Key references include:
* Box & Jenkins (2015) – Time Series Analysis
* Breiman (2001) – Random Forests
* Engle (1982), Bollerslev (1986) – ARCH/GARCH Models
* Hastie, Tibshirani & Friedman (2017) – The Elements of Statistical Learning
(Full references are available in the research paper.)

## Author
* Aman Kumar Singh
* www.linkedin.com/in/aman-kumar-singh-71a090206
* aksingh1652@gmail.com

