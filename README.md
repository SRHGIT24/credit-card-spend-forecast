# Credit-Card-Spend-Forecasting (Prophet)

Forecast monthly credit-card spend for a chosen **city + expense category** using Facebook/Meta **Prophet**.  
Includes data loading, monthly aggregation, a time-based train/test split, 6-month forecasts with uncertainty bands, MAE evaluation, and plots.

---

## 🗂 Files

- **`notebooks/1_prophet_forecast.ipynb`**  
  End-to-end pipeline:
  - Load & aggregate monthly spend (`ds`, `y` for Prophet)
  - Train/test split (last **6 months**)
  - Fit Prophet (yearly seasonality)
  - Forecast **6 months** ahead with intervals
  - Compute **MAE** on holdout
  - Save plots: forecast & components

- **`data/Credit card transactions - India - Simple.csv`**  
  Source CSV used by the notebook.

- **`notebooks/assets/`**  
  Generated figures (`monthly_spend_plot.png`, `prophet_forecast.png`, `prophet_components.png`).

---

## ⚡ Quick Start

1. **Clone**
   ```bash
   git clone git@github.com:SRHGIT24/credit-card-spend-forecast.git
   cd credit-card-spend-forecast


🧰 Tech Stack
Language: Python 3.x
Forecasting: prophet
Data: pandas, numpy
Visualization: matplotlib
Evaluation: scikit-learn (MAE)
Environment: Jupyter Notebook
