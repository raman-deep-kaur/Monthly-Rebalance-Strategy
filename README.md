# Monthly-Rebalance-Strategy
A momentum-based long-short equity strategy that rebalances monthly to optimize portfolio performance using historical price trends.

This project implements a quantitative long-short equity trading strategy based on 3-month momentum signals. The strategy selects the top 10 performing stocks (long) and the bottom 10 underperformers (short) each month, allocating a fixed portion of capital to each position. Portfolio rebalancing occurs at the start of each month, and trades are executed based on momentum rankings derived from historical price data.

Key features:

Monthly rebalancing using momentum calculated over a 63-trading-day (approx. 3 months) lookback window.

Equal-weighted long and short allocations (5% each of total capital).

Trades, positions, and cash flow are recorded for analysis.

Developed in Python using only core libraries: numpy, pandas, and datetime.

The goal is to maximize the Sharpe Ratio of the portfolio while maintaining a systematic, rules-based approach suitable for backtesting and performance evaluation.
