Nasdaq Futures Time-Series Analysis & Strategy Backtesting (2025)

Author

Obaida aladday

---

Project Overview

This project analyzes Nasdaq Futures (NQ) market data using:

- 1-minute timeframe
- 15-minute timeframe

The analysis focuses on 2025 market data only.

The project includes:

- Data preprocessing
- Data validation
- Statistical analysis
- Time-series analysis
- ADF stationarity testing
- Volatility analysis
- Feature engineering
- Trading strategy development
- Strategy backtesting

---

Trading Strategy

A simple Long-Only Trend Following Strategy was implemented on the 15-minute timeframe.

Entry Conditions (BUY)

- Price > EMA50
- Volume > Average Volume (20)

Exit Conditions (SELL)

- Price < EMA50

The strategy was intentionally designed to remain simple, interpretable, and avoid overfitting.

---

Backtesting Metrics

The strategy performance was evaluated using:

- Cumulative Return
- Maximum Drawdown
- Win Rate
- Total Trades
- Sharpe Ratio
- Equity Curve

---

Required Libraries

Install dependencies using:

pip install -r requirements.txt

Libraries used:

- numpy
- pandas
- matplotlib
- seaborn
- plotly
- scipy
- statsmodels
- jupyter

---

How to Run the Project

1. Open Jupyter Notebook

Run:

jupyter notebook

2. Open the notebook file

Obaidaaladday_Alzghoul_NQ_Analysis_2025.ipynb

3. Run all cells

Execute the notebook from top to bottom.

---

Important Notes

- Only 2025 market data was analyzed.
- No missing values or duplicate records were detected.
- Time-series chronological order was verified.
- The 15-minute timeframe was selected for strategy implementation due to reduced market noise compared to 1-minute data.
- This project prioritizes interpretability and analytical reasoning over model complexity.
