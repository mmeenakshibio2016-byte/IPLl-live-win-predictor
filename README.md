# IPL Live Win Predictor (Streamlit + XGBoost)

This project predicts the winning team during the second innings of an IPL match
using ball-by-ball data and an XGBoost classification model.

## Features
- Real-time win probability prediction
- Chase-specific feature engineering
- Match-wise train-test split (no data leakage)
- Streamlit-based interactive UI

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Streamlit

## How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
