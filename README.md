# Credit Card Spend Forecasting with Prophet

**Project Overview**  
This repository walks through a complete monthly forecasting pipeline using Facebook Prophet. We start with a Kaggle dataset of credit-card transactions in India, aggregate daily transactions into monthly spend for a specific city & expense type, and then use Prophet to predict the next six months of spending.

---

## Repository Structure

```text
credit-card-spend-forecast/
├── LICENSE
├── .gitignore
├── README.md
├── requirements.txt
├── data/
│   └── README.md
├── notebooks/
│   ├── 1_prophet_forecast.ipynb
│   └── assets/
│       ├── monthly_spend_plot.png
│       ├── prophet_forecast.png
│       └── prophet_components.png
└── src/
    ├── __init__.py
    └── data_utils.py
