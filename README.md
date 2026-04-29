# Markov-Credit-Dynamics : Stochastic Credit Risk Modeling 📉⛓️

## 📖 Overview
This repository contains an MSc Statistics project focusing on **Corporate Credit Risk Analysis** using **Discrete-Time Markov Chains (DTMC)**. 

A firm's credit rating at any given time is treated as a state within a Markov chain. By utilizing historical corporate credit ratings alongside comprehensive financial ratios, this project models how companies transition between different credit health states—from highly rated (AAA) down to absorbing default states.

## ✨ Key Concepts Applied
- **Transition Probability Matrices ($P$):** Building empirical rating migration matrices.
- **Chapman–Kolmogorov Equations:** Forecasting multi-year credit migrations via matrix exponentiation ($P^2, P^3...$).
- **Stationary Distributions ($\pi$):** Analyzing the long-run distribution of corporate credit ratings.
- **Absorbing States & Gambler's Ruin:** Evaluating the absorption into the "Default" state.
- **Mean First Passage Time:** Calculating the expected number of years before a firm defaults based on its current rating.

## 📊 Dataset
The analysis is powered by the `corporateCreditRatingWithFinancialRatios.csv` dataset, which includes:
- **Categorical Data:** Rating Agencies (e.g., S&P, Moody's), Sectors, and Tickers.
- **Credit Ratings:** Historical ratings mapped to numerical/stochastic states.
- **Financial Ratios:** Current Ratio, Debt/Equity, Gross/Operating Margins, ROE, ROA, Cash Flow metrics, and more.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Environment:** Jupyter Notebook (`code.ipynb`)
- **Key Libraries:** `pandas`, `numpy`, `matplotlib` / `seaborn` (for transition heatmaps and distributions)

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/Amber-s-art/Markov-Credit-Dynamics.git](https://github.com/Amber-s-art/Markov-Credit-Dynamics.git)
