# 📈 Stock & Asset Trend Analysis Tool

A Python-based command-line application for analyzing and forecasting the trends of various financial assets, including global stocks, Thai stocks, gold, and cryptocurrencies. 

This tool fetches historical market data, calculates key technical indicators, and provides a 7-day statistical price forecast along with comprehensive data visualization.

## ✨ Features

* **Multi-Asset Support:** Analyze US Stocks (e.g., AAPL, TSLA), Thai Stocks (e.g., PTT.BK), Global Gold (GC=F), and Cryptocurrencies (e.g., BTC-USD).
* **Customizable Timeframes:** Choose between short-term (20 days), medium-term (50 days), long-term (200 days), or set a custom historical period.
* **Technical Indicators Included:**
    * **Zig Zag Indicator:** Auto-adjusts based on market volatility to identify significant swing highs and lows.
    * **RSI (Relative Strength Index):** 14-day RSI to identify overbought/oversold conditions.
    * **MACD (Moving Average Convergence Divergence):** Standard (12, 26, 9) parameters with signal lines and histograms.
    * **Linear Regression Trend Line:** Identifies the current overall market direction.
* **7-Day Forecasting:** Predicts the price trajectory for the next 7 working days based on linear regression statistics.
* **Comprehensive Visualization:** Generates a 4-tier interactive chart using Matplotlib (Price Action, Volume, RSI, and MACD).
* **Bilingual Summary:** Outputs analysis summaries in both English and Thai.

## 🛠️ Prerequisites

Before running this project, ensure you have Python installed on your system. You will also need to install the required libraries.

```bash
# Install the required dependencies
pip install -r requirements.txt.txt