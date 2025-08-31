# stock-market-analysis-and-prediction-master
# 📈 Stock Market Analysis and Prediction

---

## 🔹 Introduction
**Stock Market Analysis and Prediction** is a project on **technical analysis, visualization, and prediction** using data from Google Finance/Yahoo Finance.  

By analyzing historical stock data of leading **technology companies and other major stocks**, the project:
- Retrieves stock data using **Pandas**  
- Visualizes trends with **Matplotlib/Seaborn**  
- Analyzes **risk factors** (returns, volatility, correlation, Value at Risk)  
- Predicts future stock prices using the **Monte Carlo simulation method**  

---

## 🔹 Purpose
The purpose of this project is to:
- **Comparatively analyze** the effectiveness of prediction techniques on stock market data  
- Provide **insights** into stock behavior through visualization  
- Estimate **risk exposure** and **Value at Risk (VaR)** for different stocks  
- Explore **future stock price predictions** using Monte Carlo simulation  

This project combines concepts from:
- **Data Mining**  
- **Statistics**  
- **Financial Risk Analysis**  

---

## 🔹 Workflow
1. **Data Collection** – Fetched stock data from Yahoo Finance using `pandas_datareader`.  
2. **Exploratory Data Analysis (EDA)** – Studied stock price trends, trading volume, and moving averages.  
3. **Daily Returns & Risk Analysis** – Calculated daily returns, volatility, and plotted histograms.  
4. **Correlation Analysis** – Compared multiple stocks using correlation matrices & heatmaps.  
5. **Value at Risk (VaR)** – Estimated downside risk with quantiles and Monte Carlo simulation.  
6. **Monte Carlo Simulation** – Simulated future price paths with **Geometric Brownian Motion (GBM)**.  

---

## 🔹 Results & Insights
- **Google & Amazon returns are highly correlated**  
- **Apple & Microsoft show lower risk exposure** than Amazon & Google  
- **Monte Carlo simulation highlights downside risk** with 95% and 99% confidence intervals  
- Example: With $1M invested in Apple, **5% daily VaR ≈ $16,000 potential loss**  

---

## 🔹 Tech Stack
- **Python 3.x**
- **NumPy** – numerical computation  
- **Pandas** – stock data processing  
- **Matplotlib & Seaborn** – visualization  
- **pandas_datareader / yfinance** – fetching financial data  

---

## 🔹 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/SawKunal/stock-market-analysis.git
   cd stock-market-analysis
