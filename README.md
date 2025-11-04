# CAPM Model (Streamlit App)

This project is a **Streamlit-based interactive web app** that implements the **Capital Asset Pricing Model (CAPM)** to analyze the relationship between a stock’s risk and its expected return.  
It allows users to select multiple stocks, fetch real-time data from Yahoo Finance, and visualize their performance, risk (beta), and expected returns compared to the S&P 500.

---

## 🚀 Features

- Select up to **4 stocks** (e.g., TSLA, AAPL, AMZN, GOOGL, etc.)
- Choose a custom **time range (1–10 years)**  
- **Fetch real-time data** from Yahoo Finance & FRED
- Display:
  - Head and tail of the stock dataset
  - Interactive price charts (raw and normalized)
  - Daily returns of each stock
  - Calculated **Beta** (systematic risk)
  - **Expected return** (based on CAPM formula)

---

## 🧠 How It Works

The CAPM formula used:

\[
E(R_i) = R_f + \beta_i (E(R_m) - R_f)
\]

Where:  
- \( E(R_i) \): Expected return of the stock  
- \( R_f \): Risk-free rate (assumed 0 here)  
- \( \beta_i \): Beta value of the stock  
- \( E(R_m) \): Expected return of the market (S&P 500)

---

## 🗂️ Project Structure

