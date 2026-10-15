
# Credit Card Fraud Detection

An educational machine learning project for transaction risk analysis.

## Features
- Synthetic transaction data
- Random Forest classifier
- Transaction risk prediction demo
- Model evaluation metrics
- Dashboard charts
- CSV export

## Tech Stack
- Python
- Pandas and NumPy
- Scikit-learn
- Streamlit
- Matplotlib

## Setup

Create a virtual environment and install dependencies:

Powershell:

```bash
python -m venv .venv
```

Windows CMD:

```bat
.venv\Scripts\activate.bat
```

Install packages and start the dashboard:

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Dataset and Safety
The initial version uses synthetic demo data. Its
predictions are not suitable for real banking decisions.
No real customer or card data is required.
