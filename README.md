# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin Fear & Greed sentiment affects trader behavior and performance on Hyperliquid.

## Methodology
- Aggregated trades per account per day
- Merged with Bitcoin Fear & Greed Index
- Analyzed PnL, win rate, and position size by sentiment

## Key Insights
- Extreme Fear shows highest volatility and drawdowns
- Greed regimes have higher position sizes
- Sentiment impacts risk-taking more than average profit

## Strategy Recommendations
1. Reduce position size by 30–40% during Fear/Extreme Fear
2. During Greed, allow higher trade frequency but cap exposure

## How to Run
1. Install Python 3.x
2. Place sentiment.csv and trades.csv in `data/`
3. Run notebook.ipynb
