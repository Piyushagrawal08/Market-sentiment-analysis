# 📊 Market Sentiment Analysis

## 📌 Project Overview

This project explores the relationship between **trader behavior**
(profitability, risk, volume, leverage) and **market sentiment** (Fear
vs. Greed).\
The goal is to identify hidden patterns that can improve trading
strategies in volatile crypto markets.

We used:\
- **Bitcoin Market Sentiment Dataset** (Fear & Greed Index)\
- **Historical Trader Data from Hyperliquid**

------------------------------------------------------------------------

## 📂 Repository Structure

    ds_PiyushAgrawal/
    ├── notebook_1.ipynb          # Main Colab notebook with full analysis
    ├── csv_files/                # Processed or intermediate datasets
    │   └── *.csv
    ├── outputs/                  # Generated plots & charts
    │   ├── avg_risk_exposure_by_sentiment.png
    │   ├── pnl_distribution_by_sentiment.png
    │   ├── risk_vs_sentiment.png
    │   └── volume_vs_sentiment.png
    ├── ds_report.pdf             # Final summarized report with insights
    └── README.md                 # Project documentation

------------------------------------------------------------------------

## 🚀 How to Run the Notebook

1.  Open the notebook in **Google Colab**:\
    [notebook_1.ipynb](https://colab.research.google.com/github/Piyushagrawal08/Market-sentiment-analysis/blob/main/notebook_1.ipynb)

2.  Ensure dependencies are installed (Pandas, NumPy, Matplotlib,
    Seaborn, etc.)

3.  Run the notebook step by step to reproduce results.

------------------------------------------------------------------------

## 📊 Key Insights

-   **Risk Exposure:** Traders take significantly higher risks during
    *Extreme Fear* (avg. \~25k USD exposure).\
-   **PnL Distribution:** Median PnL remains near zero across
    sentiments, with extreme gains/losses observed.\
-   **Trade Size:** Larger trades occur during *Extreme Fear*,
    suggesting contrarian behavior.\
-   **Sentiment Impact:** Fear phases trigger overexposure, while greed
    phases show more controlled trading.

------------------------------------------------------------------------

## 📑 Report

The detailed analysis, visuals, and insights are available in the
[ds_report.pdf](./ds_report.pdf).

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **Python** (Pandas, NumPy, Matplotlib, Seaborn)\
-   **Google Colab**\
-   **GitHub** for version control

------------------------------------------------------------------------

## 👤 Author

**Piyush Agrawal**\
Final Year B.Tech -- Information Technology\
Data Analytics Enthusiast
