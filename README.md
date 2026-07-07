# Bitcoin Market Sentiment vs Hyperliquid Trader Performance

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance on the Hyperliquid platform. By combining the Bitcoin Fear & Greed Index with historical trading data, the analysis investigates whether market sentiment influences trading behavior, profitability, and overall trading performance.

The objective is to identify meaningful patterns that can support better trading decisions and provide actionable strategy recommendations.

---

## Datasets

### 1. Bitcoin Fear & Greed Index

Contains daily market sentiment information.

**Columns**

* Date
* Sentiment Classification (Fear, Extreme Fear, Greed, Extreme Greed)
* Sentiment Score

### 2. Hyperliquid Historical Trader Data

Contains historical trading activity.

**Key Columns**

* Account
* Coin
* Execution Price
* Size Tokens
* Size USD
* Direction
* Closed PnL
* Fee
* Timestamp

---

## Project Workflow

1. Load both datasets.
2. Inspect dataset dimensions, missing values, and duplicates.
3. Convert timestamps into a common date format.
4. Merge trading data with daily market sentiment.
5. Perform feature engineering by creating metrics such as Win/Loss and daily trading statistics.
6. Conduct exploratory data analysis using statistical summaries and visualizations.
7. Segment traders based on trading behavior and performance.
8. Generate insights and strategy recommendations.

---

## Analysis Performed

* Dataset inspection
* Missing value analysis
* Duplicate record analysis
* Timestamp conversion
* Dataset merging
* Daily Profit and Loss analysis
* Win rate analysis
* Trading volume analysis
* Average trade size analysis
* Long vs Short ratio analysis
* Fee analysis
* Top trader identification
* Coin-wise profitability analysis
* Sentiment-wise profitability analysis
* Trader segmentation
* Correlation analysis

---

## Key Insights

* Market sentiment influences trader profitability and trading activity.
* Trading performance differs across Fear and Greed market conditions.
* Trading behavior changes with market sentiment, including differences in trade frequency and position sizing.
* A relatively small group of traders contributes a significant portion of total profits.
* Certain cryptocurrencies consistently generate higher profitability than others.

---

## Strategy Recommendations

* Reduce position size and manage risk more conservatively during Fear and Extreme Fear market conditions.
* Increase trading activity only when supported by favorable market sentiment and strong risk management practices.
* Monitor market sentiment alongside trading metrics to improve decision-making.
* Focus on disciplined trade execution rather than increasing trade frequency during uncertain market conditions.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn (for clustering)

---

## Repository Structure

```
├── notebook.ipynb
├── README.md
├── report.pdf
├── charts/
├── outputs/
└── data/
```

---

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload both datasets.
3. Run all cells sequentially.
4. The notebook will generate all analyses, visualizations, and summary tables automatically.

---

## Conclusion

This project demonstrates how combining market sentiment with historical trading data can reveal meaningful behavioral patterns and profitability trends. The insights obtained can assist traders in improving decision-making, managing risk, and developing more informed trading strategies.
