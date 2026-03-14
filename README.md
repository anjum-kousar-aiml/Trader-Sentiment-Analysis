# Trader Performance vs Market Sentiment Analysis

## Overview
This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance.  
The analysis uses trader activity data along with Bitcoin market sentiment data to identify patterns and insights that could help inform trading strategies.

## Datasets
Two datasets were used in this analysis:

1. **Bitcoin Market Sentiment Dataset**
   - Contains daily market sentiment classification (Fear or Greed).

2. **Historical Trader Data (Hyperliquid)**
   - Contains trader activity including account, trade size, trade direction, and profit/loss.

## Dataset Access

Due to GitHub file size limits, the datasets are hosted on Google Drive.

Dataset folder:
[https://drive.google.com/drive/folders/1Oa8cYTEu9AGr8_eO8KgwreMcsnm68i4m?usp=sharing]

## Methodology
The analysis was performed in the following steps:

1. Data loading and inspection
2. Data cleaning and preparation
3. Aligning datasets using the date column
4. Feature creation including:
   - Daily PnL per trader
   - Win rate
   - Average trade size
   - Number of trades per day
   - Long vs Short ratio
5. Behavioral analysis during Fear vs Greed periods
6. Trader segmentation
7. Insights and strategy recommendations
8. Optional predictive model for profitability classification

## Key Insights
The analysis highlights differences in trader performance and behavior during Fear and Greed market conditions.  
These insights can help traders adjust their strategies based on market sentiment.

## Files Included
- `trader_sentiment_analysis.ipynb` – Jupyter notebook containing the full analysis

## How to Run
1. Open the notebook in Jupyter Notebook or Jupyter Lab.
2. Run the cells sequentially from top to bottom to reproduce the analysis.
