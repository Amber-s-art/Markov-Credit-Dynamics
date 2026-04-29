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

2. Ensure you have the required dependencies installed (e.g., `pip install -r requirements.txt`).
3. Open `code.ipynb` in Jupyter Notebook or JupyterLab.
4. Ensure `corporateCreditRatingWithFinancialRatios.csv` is in the same directory as the notebook and run the cells.

## 🔮 Future Work & Extensions
While this project establishes a robust baseline for modeling credit migrations stochastically, several exciting avenues can be explored in the future:
1. **Interactive Visualization:** Building an interactive dashboard using Power BI to filter and visualize the financial ratios and rating distributions across different corporate sectors over time.
2. **Machine Learning Integration:** Train predictive classification models on the financial ratios (ROE, Debt/Equity, etc.) to predict *individual* transition probabilities rather than relying solely on historical empirical averages.
3. **Continuous-Time Markov Chains (CTMC):** Upgrade the discrete model to a continuous framework, allowing for default events to be modeled at random intervals rather than fixed annual steps.
4. **Macroeconomic Stress Testing:** Condition the transition matrices on macroeconomic variables (e.g., interest rates, GDP growth) to see how credit migrations behave during recessions versus economic booms.

## 📝 License
This project is licensed under the MIT License.
