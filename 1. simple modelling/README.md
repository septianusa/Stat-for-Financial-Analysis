# Simple trading strategy using Moving Average
## Objective
The moving average (MA) is a simple technical analysis tool that smooths out price data by creating a constantly updated average price. The average is taken over a specific period of time, like 10 days, 20 minutes, 30 weeks or any time period the trader chooses.

MA of short period is more closely associated with recent changes of stock price, then called as fast signal. MA over long period reflects the price change over long-term history then called as slow signal.

Some traders believes if fast signal > slow signal the stock price will goes up in next several days. Otherwise, the price will decrease. Using this strategy we will try to make some profit based on MA signal.

## Case Study
Stock Code : BBCA (IDX Market)

Training data period: Jan 1, 2019 - Dec 31, 2019

Strategy : If fast signal > slow signal, we will buy and hold one share of stock.
