# quant-trading-strategies
Machine Learning and Quantitative Strategies for Algorithmic Trading


# Project 1:

## Overview
In this project, we apply machine learning and quantitative analysis to develop an algorithmic trading strategy using S&P 500 stock data.

## Steps Undertaken

- **Download S&P 500 Stock Prices Data**
  - Historical stock price data is obtained for analysis.

- **Calculate Technical Indicators**
  - A variety of technical indicators and features for each stock are computed.

- **Monthly Aggregation**
  - Data is aggregated on a monthly basis, focusing on the top 150 most liquid stocks.

- **Monthly Returns Calculation**
  - We calculate monthly returns for different time horizons to enhance our feature set.

- **Rolling Beta Calculation**
  - Fama-French Factors are downloaded to calculate rolling beta values for each stock.

- **K-Means Clustering**
  - A K-means clustering model is applied monthly to group similar assets based on their features.

- **Portfolio Construction**
  - Assets are selected each month based on their cluster and used to form a portfolio via Efficient Frontier optimization, targeting maximum Sharpe ratio.

- **Visualize Portfolio Performance**
  - The returns of our constructed portfolio are visualized and compared to the benchmark S&P 500 returns.

## Limitation

> :warning: **Survivorship Bias**: This project uses the most recent S&P 500 stocks list, which introduces survivorship bias. For real-life applications, it is advisable to use data that accounts for companies that no longer exist or have been removed from the index.
