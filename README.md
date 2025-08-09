Trader Behavior Insights – Junior Data Scientist Task

# Overview
This project analyzes the relationship between Bitcoin market sentiment and trader performance.  
The goal is to uncover patterns that can drive smarter trading strategies in the Web3 space.



# Datasets
1. Historical Trader Data (Hyperliquid)**  
Contains detailed trade records including:  
`account`, `symbol`, `execution_price`, `size`, `side`, `time`, `start_position`, `event`, `closedPnL`, `leverage`, etc.

2. Bitcoin Fear & Greed Index  
Contains daily sentiment classifications:  
`date`, `classification` (Fear / Greed / Extreme Fear / Extreme Greed)

---

# Methodology
1. Load datasets and inspect basic structure
2. Convert timestamps and align on a common date format
3. Merge trader data with sentiment data by date
4. Calculate key performance metrics:
   - Average and median closed PnL
   - Win rate per sentiment class
   - Trade counts
5. Analyze long vs short performance under different sentiments
6. Explore leverage patterns
7. Visualize findings using bar charts, scatter plots, violin plots, and heatmaps
8. Summarize insights for trading strategy implications

---

# Key Insights
- **Highest average PnL** tends to occur during **Greed** sentiment.
- **Lowest average PnL** observed during **Extreme Fear**.
- **Long positions** perform better in Greed phases, while **short positions** fare better during Fear.
- Leverage usage spikes during Greed, increasing both profit potential and loss risk.
- Sentiment shifts often precede changes in average PnL.

---

# How to Run
1. Open the Jupyter Notebook in Google Colab.
2. Upload the datasets when prompted:
   - `historical_data.csv`
   - `fear_greed_index.csv`
3. Run all cells sequentially.
4. Review visualizations and summary insights.

---

**Author:** DEBANKSH GUHA
**Date:** 09/08/2025
