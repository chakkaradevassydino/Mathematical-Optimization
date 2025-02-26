

1. Portfolio Optimization using Modern Portfolio Theory (MPT)

Overview

This project implements Modern Portfolio Theory (MPT) to optimize stock allocation, maximizing returns while minimizing risk using mathematical optimization techniques.

Features

Fetches real-time stock data using Alpha Vantage API

Computes daily returns, expected returns, and risk (covariance matrix)

Uses SciPy's minimize function for optimization

Plots the Efficient Frontier



# 📊 Portfolio Optimization using Modern Portfolio Theory (MPT)

## 📌 Overview

This project demonstrates **Portfolio Optimization** using **Modern Portfolio Theory (MPT)**, developed by **Harry Markowitz**. The objective is to determine the best allocation of investments to maximize returns while minimizing risk using **mathematical optimization techniques**.

## 🚀 Features

- Fetches real-time stock data using **Alpha Vantage API** 📈
- Computes **daily returns**, **expected returns**, and **risk (covariance matrix)** 🔢
- Utilizes **SciPy's `minimize` function** for portfolio optimization 📊
- Plots the **Efficient Frontier** to visualize optimal portfolios 🖼️
- Identifies the **optimal risk-return trade-off portfolio** ⭐

## 📂 Project Structure

```
Portfolio-Optimization/
│── stock_data.csv               # Saved stock price data
│── portfolio_optimization.ipynb # Jupyter Notebook with full implementation
│── README.md                    # Project description (this file)
```

## 🛠 Installation & Setup

1. **Clone this repository**:

   ```sh
   git clone https://github.com/your-username/Portfolio-Optimization.git
   cd Portfolio-Optimization
   ```

2. **Install required Python libraries**:

   ```sh
   pip install pandas numpy matplotlib scipy alpha_vantage
   ```

3. **Obtain a free API key from Alpha Vantage**:

   - Sign up at [Alpha Vantage](https://www.alphavantage.co/support/#api-key)
   - Replace `YOUR_ALPHA_VANTAGE_API_KEY` in the code with your personal key

4. **Run the Jupyter Notebook**:

   ```sh
   jupyter notebook
   ```

## 📊 Example Results

### **Optimal Portfolio Allocation:**

```
AAPL: 25.12%
MSFT: 30.45%
GOOGL: 20.22%
AMZN: 15.78%
TSLA: 8.43%
```

### **Efficient Frontier Visualization:**

The chart below illustrates different portfolio combinations. The **red star** represents the optimal risk-return trade-off portfolio.

*(Run the notebook to generate this image)*

## 🎯 Why This Project Matters

✅ Uses **real financial market data**✅ Demonstrates **mathematical optimization concepts**✅ Enhances **data science and finance skills**✅ Valuable for **technical interviews and portfolio showcases** 🎓

---

## 📢 Contributions & Feedback

Feel free to fork this repository, suggest improvements, or reach out if you have questions! Collaboration and feedback are always welcome. 🚀
