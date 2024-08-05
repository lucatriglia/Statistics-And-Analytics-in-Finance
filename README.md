# Financial Analysis Projects

This repository contains a collection of Jupyter notebooks showcasing various financial analysis projects I worked on during my Masters in Finance at the National University of Singapore (NUS).

### 1) Underperforming_ETF_Strategy_Backtesting.ipynb

This notebook investigates an investment strategy of constructing portfolios from underperforming actively managed ETFs. The key hypothesis is that funds with poor recent performance may tend to revert to the mean and be poised for a rebound. Key features of the analysis include:

* Multi-factor model analysis using Fama-French 5 factors (Market, Size, Value, Profitability, Investment)
* ETF selection based on negative alpha values over rolling 2-year periods
* Portfolio construction methods explored:
   * Equal Weight
   * Maximum Sharpe Ratio
   * Maximum Sharpe Ratio with L2 Regularization
   * Minimum Volatility
   * Minimum Volatility with L2 Regularization
* Comprehensive backtesting of the strategy over multiple time periods
* Statistical analysis of results, including t-tests comparing strategy performance to benchmarks

**Results:**
The study found that portfolios constructed from recently underperforming ETFs demonstrated potential for outperformance:

1. The Maximum Sharpe Ratio portfolio with L2 Regularization consistently outperformed both equal-weight and minimum volatility approaches.
2. The strategy showed statistically significant outperformance compared to the S&P 500 benchmark in 3 out of 4 tested periods.
3. Portfolios exhibited lower volatility than the broad market, suggesting a potential diversification benefit.
4. The approach was most effective during periods of market recovery, indicating its potential as a contrarian strategy.

However, transaction costs and the potential for strategy decay over time were noted as areas requiring further investigation.


### 2) Python - Portfolio Value at Risk.ipynb

Explores the concept of Value-at-Risk (VaR), including:
- Calculation of VaR using different methods
- Visualization of VaR for various portfolios
- Comparison of empirical and theoretical VaR


### 3) Python - Portfolio Performance Attribution and Factor Model.ipynb

Analyzes portfolio performance using factor models, covering:
- Performance attribution techniques
- Implementation of multi-factor models
- Visualization of factor exposures


### 4) Python - Portfolio Optimization.ipynb

Demonstrates various portfolio optimization techniques, including:
- Mean-variance optimization
- Maximum Sharpe ratio portfolios
- Minimum volatility portfolios


### 5) Python - Financial concepts.ipynb

Covers fundamental financial concepts and calculations, such as:
- Time value of money
- Bond pricing and yield calculations
- Option pricing basics

## Usage:

To use these notebooks:

1. Ensure you have Jupyter Notebook installed.
2. Install required libraries (pandas, numpy, matplotlib, etc.).
3. Open the desired notebook and run the cells sequentially.

**Note:** Some notebooks may require additional setup for data access (e.g., API keys for financial data providers).

Feel free to explore the notebooks and reach out if you have any questions!
