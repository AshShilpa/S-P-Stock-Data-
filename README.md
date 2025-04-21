# S-P-Stock-Data-
"""
📘 Project Title: Exploratory Data Analysis of S&P 500 Companies and Historical Stock Performance

🔍 Objective:
This project performs a comprehensive Exploratory Data Analysis (EDA) on a merged dataset of S&P 500 financial metrics and historical stock prices. It utilizes Python and libraries such as Pandas, Matplotlib, Seaborn, and SciPy to derive insights, identify patterns, and visualize trends in company performance, stock volatility, and sector-wise behavior.

📦 Kaggle Datasets Used:
1. **S&P 500 Company Financials**: Includes EPS, Market Cap, P/E Ratio, Dividend Yield, and other metrics.
2. **Stock Prices (5-Year)**: Historical OHLC (Open, High, Low, Close) stock price data with trading volumes.

📈 Key Features:
- Data cleaning, transformation, and normalization
- Sector-wise aggregation and analysis
- Rolling metrics (average, standard deviation)
- Advanced visualizations including KDE plots, strip plots, and regression
- Statistical summaries including correlation, skewness, and kurtosis

📤 Output:
- Cleaned and transformed dataset (`merged_financials_cleaned.csv`, `.json`) with derived features like z-score, rolling average, and category labeling
- A wide range of visualizations (line plots, bar charts, boxplots, KDE plots, regression plots)
- Correlation matrices and summary statistics
- Missing value diagnostics and resolved gaps in critical columns

🔍 Key Discoveries & Insights:
- 📈 **Technology & Healthcare sectors** consistently outperformed in average stock price and EPS.
- 📉 **Volatility analysis** via rolling standard deviation helped identify high-risk stocks (e.g., TSLA, AMZN).
- 💡 **EPS positively correlates** with price, confirmed through correlation matrix and regression analysis.
- 📦 **Sector boxplots** showed distinct EPS and price distributions, highlighting value sectors vs. growth sectors.
- 🧪 **Z-score and normalization** were effective in detecting stock price outliers.
- 🛠 **All missing or inconsistent values were handled**, resulting in a modeling-ready dataset.

🛠 Technologies:
- Python, Pandas, Matplotlib, Seaborn, Scipy, Pandas Profiling, Swifter

"""
