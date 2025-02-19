# Stock Portfolio Optimization using Simulated Annealing

This repository contains Python code that performs stock portfolio optimization using the Simulated Annealing algorithm. The code retrieves 20 years of daily stock data for a list of stock tickers, calculates average returns, and optimizes the portfolio's weights to maximize the expected return.

## Overview

The code performs the following steps:

1. **Data Retrieval**: 20 years of daily stock data is retrieved using the Yahoo Finance API (yfinance).
2. **Average Return Calculation**: The average daily return is calculated for each stock.
3. **Simulated Annealing Optimization**: The Simulated Annealing algorithm is used to optimize the portfolio weights, aiming to maximize the expected return.
4. **Results Display**: The optimized portfolio weights, expected return of each stock, and investment amounts are displayed.

## Stocks Analyzed

The analysis includes the following stocks:
- RELIANCE.NS
- INFY.NS
- HDFCBANK.NS
- LT.NS
- HINDUNILVR.NS
- ASIANPAINT.NS
- MARUTI.NS
- TITAN.NS
- TATAMOTORS.NS
- SUNPHARMA.NS

You can modify this list to include different stocks based on your analysis requirements.

## Usage

To run the code:

1. Install the required Python packages: numpy, pandas, yfinance.
   ```
   pip install numpy pandas yfinance
   ```
2. Clone the repository:
   ```
   git clone https://github.com/ShreyasDole/stock-portfolio-optimization.git
   ```
3. Navigate to the project directory:
   ```
   cd stock-portfolio-optimization
   ```
4. Run the Python script:
   ```
   python portfolio_optimization.py
   ```

## Results

Upon running the code, you will see the optimized portfolio weights, expected return of each stock, and the recommended investment amounts for each stock.

