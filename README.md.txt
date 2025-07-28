# Crash Game Predictor (Improved)
Predict whether the next multiplier will be above or under 2.0 using weighted confidence logic.

## Features
- Upload CSV or enter data manually
- Confidence uses:
  - Weighted historical data
  - Trend and streak adjustment
  - Volatility control
  - Normalization for small datasets

## Run locally:
pip install -r requirements.txt
streamlit run app.py
