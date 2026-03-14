Traders Performance V/S Market Sentiment Analysis

Objective
This project aims to analyze the market sentiments influence on the trader behaviours and suggest the rule of thumb strategies for them.

Dataset
Two datasets were used:
1. Market Sentiment Dataset
Contains daily sentiment classification.
  Columns:
    date
    sentiment classification
    sentiment value
    timestamp
2. Hyperliquid Trader Dataset
Contains historical trade data including:
  account
  trade size
  trade direction
  execution price
  closed PnL
  timestamp
Methodology
1.Data Cleaning
  -Removed duplicates
  -Checked missing values
  Converted timestamps to datetime
2.Data Alignment
  -Aggregated trades to daily level
  -Merged trading data with sentiment data using date
3.Feature Engineering
  -Daily PnL per trader
  -Win rate
  -Average trade size
  -Trade frequency
  -Long vs short ratio
4. Behavioral Segmentation
  -Frequent vs infrequent traders
  -Risk exposure using trade size
5.Key Insights
  -Trader performance varies with sentiment
      Win rates and PnL tend to be higher during Greed periods, indicating traders perform better when the market is optimistic.
   -Risk-taking behavior increases during Greed
      Average trade sizes are larger during Greed periods, suggesting traders increase capital exposure when sentiment is bullish.
    -Frequent traders generate higher profits
      Highly active traders show significantly higher total PnL compared to infrequent traders, although they also face higher volatility.
6. Recommended Strategies
    -Strategy 1 - Risk Controls during Fear For ongoing fear periods: Traders should avoid excessive trading and focus on high confidence trading which reduces downside risks
   -Strategy 2 For greedy phases The trader should go for increased trade frequency with larger trade size to make bigger profits during bullish moments.

This allows traders to capitalize on bullish market momentum.
