MOMENTUN MODEL RULES SUMMARY

- Trading is only done monthly.
- Only stocks in the S&P 500 will be considered.
- Momentun slope will be calculated using 125 days.
- Top 30 stocks will be select.
- Weight will be calculated for these 30 stocks according to inverse volatility.
- Volatility is calculated using 20 day Standard devisation.
- Trend filter is positive, we are allowed to buy.
- Minimum required momentum values is set to 40.
- For each of the 30 selected stocks, if the stock has a momentum value higher than 40, we buy it. If not, we leave that calculated weight for that stock in cash.
- We sell stocks if they fall bellow the minimun required momentum value, or if they leave the index.
- Each month we rebalance and repeat.