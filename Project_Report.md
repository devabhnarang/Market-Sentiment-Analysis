# Hyperliquid Trader Performance vs Market Sentiment Analysis

## Objective

The objective of this project was to analyze how Bitcoin market sentiment, represented using the Fear & Greed Index, affects trader behavior and performance on Hyperliquid.

The analysis focused on understanding whether traders behave differently during Fear and Greed market conditions and identifying patterns that could help improve trading strategies and risk management.

---

# Datasets Used

## 1. Bitcoin Fear & Greed Index

This dataset contained daily market sentiment classifications such as Fear and Greed.

Main fields used:

* date
* classification

## 2. Hyperliquid Historical Trader Data

This dataset contained historical trading activity from Hyperliquid traders.

Main fields used:

* Account
* Side
* Size USD
* Closed PnL
* Trade ID
* Timestamp IST

---

# Data Preparation

The first step was cleaning and preparing both datasets.

The following tasks were performed:

* checked dataset dimensions
* identified missing values
* checked duplicate records
* converted timestamps into datetime format
* aligned both datasets at daily level using the date field
* merged trader activity data with market sentiment data

Additional features were also created for analysis, including:

* daily PnL
* trade frequency
* average trade size
* win rate
* long/short indicators

---

# Analysis Performed

## Fear vs Greed Comparison

Trader behavior was compared across Fear and Greed market conditions.

The analysis focused on:

* average profitability
* trading activity
* average trade sizes
* long/short participation

The results showed that Greed periods generally had:

* higher trading activity
* larger average trade sizes
* more aggressive participation

Fear periods showed comparatively more cautious trader behavior.

---

# Trader Segmentation

To better understand trader behavior, traders were grouped into different segments based on:

* trading activity
* average trade size
* profitability consistency

The main segments identified were:

* high-volume traders
* frequent traders
* consistent winners

This segmentation helped highlight differences in trader behavior and risk exposure.

---

# Clustering Bonus Analysis

As an additional analysis step, K-Means clustering was used to group traders into behavioral archetypes.

The clustering considered:

* average profitability
* average trade size
* trade frequency
* win rate

The clustering analysis helped identify groups of traders with similar trading behavior patterns.

---

# Key Insights

## 1. Market sentiment strongly influenced trader behavior

Greed periods were associated with:

* higher activity
* larger trades
* more aggressive participation

This suggests traders become more confident during optimistic market conditions.

---

## 2. Higher activity did not always improve profitability

Although traders executed more trades during Greed periods, profitability did not increase proportionally.

This may indicate emotional or impulsive trading behavior during highly optimistic market conditions.

---

## 3. Trade size distribution was highly skewed

Most trades were relatively small, while a smaller number of extremely large trades dominated the upper range.

This suggests the presence of whale or institutional-style traders in the dataset.

---

# Strategy Recommendations

## Strategy 1 — Trade More Carefully During Fear Periods

During Fear conditions, traders should reduce position sizes and avoid aggressive exposure.

A more defensive approach may help reduce downside risk and improve capital preservation during uncertain market conditions.

---

## Strategy 2 — Avoid Overtrading During Greed Periods

Greed periods showed increased trading activity, but this did not consistently improve profitability.

Traders should avoid increasing trade frequency simply because market sentiment is positive and instead focus on higher-quality setups.

---

## Strategy 3 — Focus on Consistency

The analysis suggested that traders with more stable win rates often performed better than highly active traders.

This highlights the importance of disciplined and consistent trading behavior instead of emotional decision-making.

---

# Conclusion

This project demonstrated that market sentiment has a meaningful influence on trader behavior on Hyperliquid.

Greed conditions encouraged:

* higher trading activity
* larger trade sizes
* more aggressive participation

However, increased activity did not necessarily lead to better performance.

Overall, the findings suggest that sentiment-aware risk management and disciplined trading behavior may help improve long-term trading outcomes.

