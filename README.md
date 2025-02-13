#  Advanced EDA on S&P 500 Dataset

This project performs **Advanced Exploratory Data Analysis (EDA)** on the **S&P 500** dataset from Yahoo Finance, covering trends, volatility, and seasonal patterns.

## **Project Overview**
- **Dataset**: Pulled dynamically from Yahoo Finance using `yfinance`
- **Libraries Used**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Statsmodels
- **Key Analyses**:
  - Time-series trend analysis
  - Moving Averages (50-day & 200-day)
  - Daily returns distribution
  - Volatility tracking
  - Seasonal decomposition

## **Dataset Information**
The dataset in this notebook is pulled directly from **Yahoo Finance** using the `yfinance` library. 
This means there is **no static dataset file** to include, as the code fetches live historical data each time it is run. 
I will leave it as is, without attaching a dataset – the notebook will download fresh data on execution.

## **How to Run**
1. Clone the repository.
2. Open the Jupyter Notebook and run all cells.

## **Key Insights**
- **Market Trends**: S&P 500 followed an upward trend from 2010-2020.
- **Moving Averages**: 50-day and 200-day MAs highlighted long-term market corrections.
- **Volatility**: Significant spikes during economic events.

## **Next Steps**
- Compare with FTSE 100 or other indices.
- Use Machine Learning for predictive analysis.
