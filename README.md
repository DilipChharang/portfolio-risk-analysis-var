# Portfolio Risk Analysis using Value at Risk (VaR)

## Overview

This project focuses on analyzing the risk associated with a stock portfolio using statistical and quantitative finance techniques. The objective is to estimate the potential loss that an investor may face over a one-day period under normal market conditions.

The project uses historical stock market data, statistical analysis, bootstrapping, and Value at Risk (VaR) methodology to measure portfolio risk and support investment decision-making.

---

## Problem Statement

Investors need to understand the level of risk involved in their portfolios before making investment decisions.

This project answers the following question:

**"What is the maximum expected loss of a portfolio over one day with 95% confidence?"**

---

## Objectives

* Collect historical stock market data.
* Calculate daily stock returns.
* Analyze portfolio performance and volatility.
* Study return distributions using statistical methods.
* Estimate portfolio risk using Value at Risk (VaR).
* Visualize financial data and risk metrics.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* yFinance

### Development Environment

* Jupyter Notebook
* VS Code

### Version Control

* Git
* GitHub

---

## Dataset

Historical stock price data was collected from Yahoo Finance using the yFinance API.

Sample stocks analyzed:

* Apple (AAPL)
* Microsoft (MSFT)
* Amazon (AMZN)
* Google (GOOGL)

Time Period:
2020 – 2023

---

## Project Workflow

### 1. Data Collection

Downloaded historical stock prices using the Yahoo Finance API.

### 2. Data Cleaning

Processed stock price data and prepared it for analysis.

### 3. Return Calculation

Calculated daily logarithmic returns for each stock.

### 4. Exploratory Data Analysis

Analyzed:

* Return distributions
* Volatility patterns
* Portfolio behavior

### 5. Statistical Analysis

Computed:

* Mean Return
* Standard Deviation
* Variance
* Skewness
* Kurtosis

to understand portfolio characteristics.

### 6. Confidence Interval Estimation

Estimated confidence intervals for portfolio statistics using statistical techniques.

### 7. Bootstrapping

Applied bootstrapping methods to improve risk estimation reliability.

### 8. Portfolio Construction

Created an equal-weight portfolio using selected stocks.

### 9. Value at Risk (VaR) Calculation

Calculated 1-Day 95% Value at Risk (VaR) to estimate the maximum expected portfolio loss under normal market conditions.

### 10. Data Visualization

Generated visualizations for:

* Stock Returns
* Portfolio Returns
* Risk Distribution
* VaR Analysis

---

## Key Features

* Historical stock market analysis
* Portfolio risk measurement
* Statistical modeling
* Confidence interval estimation
* Bootstrapping techniques
* Value at Risk (VaR) calculation
* Financial data visualization

---

## Results

The project successfully estimates the potential one-day loss of a stock portfolio using the Value at Risk methodology.

Key findings:

* Portfolio volatility was measured using historical returns.
* Return distributions were analyzed using statistical methods.
* VaR provided a quantitative estimate of downside risk.
* Bootstrapping improved confidence in risk estimates.

---

## Skills Demonstrated

* Python Programming
* Data Analysis
* Financial Analytics
* Statistical Analysis
* Risk Modeling
* Portfolio Analysis
* Pandas & NumPy
* Data Visualization
* Quantitative Finance

---

## Future Improvements

Potential enhancements include:

* Monte Carlo Simulation
* Machine Learning-based Risk Forecasting
* Sharpe Ratio Analysis
* Portfolio Optimization
* Interactive Dashboard using Plotly

---
