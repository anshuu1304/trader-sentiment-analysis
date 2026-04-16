# Trader Performance vs Market Sentiment Analysis

## Objective

Analyze how market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

## Datasets

* Bitcoin Market Sentiment (Fear/Greed Index)
* Historical Trader Data (Hyperliquid)

## Methodology

* Cleaned and preprocessed datasets
* Converted timestamps to daily format
* Created key metrics:

  * Daily PnL
  * Trade frequency
  * Average trade size
  * Win rate
  * Long/Short ratio
* Merged datasets based on date
* Performed sentiment-based and segment-based analysis

## Key Insights

* Trader performance is higher during Greed periods compared to Fear periods
* Trading activity and position sizes increase during bullish sentiment
* High-frequency traders tend to generate higher returns
* Larger trade sizes are associated with higher risk and reward

## Strategy Recommendations

* Reduce trading activity and position size during Fear periods to minimize risk
* Increase trading activity during Greed periods while maintaining risk control
* Focus on high-frequency strategies during strong bullish sentiment

## How to Run

1. Install required libraries:
   pip install pandas matplotlib

2. Open the notebook:
   jupyter notebook

3. Run:
   trader_sentiment_analysis.ipynb

## Author

Anshuu Shukla
