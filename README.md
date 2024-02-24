# Bachelor_Project_ESG_Investing_Backtest

#### Project Description

This thesis aimed to investigate ESG as a factor, as a long-only factor investor seeking to compose Stand-Alone, Mix or Integrated Portfolios from an asset pool consisting of S&P 100. 

We sought to utilize Python to backtest ESG as a factor (alongside Value and Growth) on S&P 100 across an approximate 10Y period, as a component in various portfolio constructions enabling us to deconstruct its return and risk properties in comparison to more well defined factors.


#### Data

Both data sources covered at least a 10Y time horizon.
- Every live company from S&P 100 (Ticker: OEX) retrieved from Bloomberg Terminal, thus approximately 100 Stocks. 
- As risk neutral rate we proxied using Fed Funds Rate, specifically ICAP US Federal Funds Rate index (annualized rate).


#### Methodology and Evaluation Metrics

In order to calculate the factors, we followed methodology of Morningstar.
Performance Metrics used include Sharpe Ratio, Information Ratio in excess of annualized return figures.
Risk metrics used include Max Drawdown, Expected Shortfall (Conditional VaR), VaR and Beta.


#### Findings

Depending on each investors risk adversity, we found the most desirable portfolio traits in risk adjusted terms to be found in a portfolio construction dictated mainly around the Growth factor throughout the backtest period, mainly ranging in the 2010-2018 period. 
A more averse investor could gravitate towards a Growth/Value mix, to increase diversity and reduce allocation risk towards a single factor. 
ESG did not provide excess return as a factor, in this particular implementation as proxied by Bloomberg and Sustainalytic Scores.


