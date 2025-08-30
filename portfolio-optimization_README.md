# Portfolio Optimization with the Markowitz Model

This project demonstrates how to use the Markowitz Mean-Variance Optimization model to find an optimal portfolio allocation with real stock market data.

## What is Portfolio Optimization?
Portfolio optimization is a quantitative method for selecting the mix of investments that maximizes return for a given level of risk (or, equivalently, minimizes risk for a given expected return). The Markowitz model (mean-variance optimization) is a foundational approach in Modern Portfolio Theory (MPT).

## What Does This Project Do?
- Downloads historical stock price data for selected tickers using [yfinance](https://github.com/ranaroussi/yfinance)
- Calculates daily returns and the covariance matrix
- Simulates random portfolios to visualize the risk-return space
- Finds the optimal portfolio weights that maximize the Sharpe Ratio (risk-adjusted return)

## How to Run

1. **Install dependencies**:
    ```bash
    pip install numpy pandas matplotlib yfinance scipy
    ```

2. **Open and run the notebook**:
    - Open `portfolio_optimization.ipynb` with Jupyter Notebook or Jupyter Lab
    - Edit the list of stock tickers as you like
    - Run all cells to see the plots and results

## Files

- `portfolio_optimization.ipynb`: Jupyter notebook with all code and explanations
- `README.md`: This file

## Example Output

- Efficient frontier plot showing simulated portfolios
- Table of optimal portfolio weights

---

**Author:** Majed Abdulaziz  
**Date:** August 2025