# Trader Performance Analysis Based on Bitcoin Market Sentiment

## Project Overview

This project investigates the relationship between Bitcoin market sentiment and trader performance using the Fear & Greed Index and Hyperliquid historical trading data.

The analysis explores how different sentiment regimes (Extreme Fear, Fear, Neutral, Greed, and Extreme Greed) influence trading activity, profitability, win rates, and position sizing behavior.

## Datasets

1. Bitcoin Fear & Greed Index Dataset

   * Date
   * Sentiment Value
   * Classification

2. Hyperliquid Historical Trading Dataset

   * Account
   * Coin
   * Execution Price
   * Size USD
   * Direction
   * Closed PnL
   * Timestamp

## Key Findings

* Fear periods generated the highest cumulative profit ($3.36M).
* Extreme Greed delivered the highest average profit per trade ($67.89).
* Extreme Greed achieved the highest win rate (46.49%).
* Traders deployed the largest average position sizes during Fear periods.
* Market sentiment serves as an effective market-regime indicator for analyzing trader behavior.
  <img width="877" height="422" alt="image" src="https://github.com/user-attachments/assets/6864cd90-7ed5-4710-a507-2d8e1bfa2bf1" />
  <img width="877" height="422" alt="image" src="https://github.com/user-attachments/assets/489f1340-73c2-46df-a83f-8771d39bda89" />



## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Repository Contents

* analysis.ipynb
* report.pdf
* charts/
* README.md
