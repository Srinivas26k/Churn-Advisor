# Customer Churn Prediction Dashboard

A comprehensive dashboard for predicting and analyzing customer churn using machine learning. Features include single customer prediction, batch processing, analytics, and business impact analysis.

## Team: Ideavaults
- Srinivas
- Hasvitha
- Srija

## Features
- Single customer churn prediction
- Batch prediction for multiple customers
- Comprehensive analytics dashboard
- Business impact analysis
- Model insights and explanations

## Local Development

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
streamlit run app.py
```

## Deployment on Streamlit Cloud

1. Push your code to a GitHub repository
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Sign in with your GitHub account
4. Click "New app"
5. Select your repository, branch, and main file (app.py)
6. Click "Deploy"

## Project Structure
```
├── app.py              # Main Streamlit application
├── models/             # Trained models
│   ├── churn_model.joblib
│   └── preprocessor.joblib
├── data/              # Data files
├── requirements.txt   # Project dependencies
└── README.md         # Project documentation
```

## Dependencies
- streamlit>=1.32.0
- pandas>=2.0.3
- numpy>=1.26.4
- scikit-learn>=1.7.0
- plotly>=6.1.2
- joblib>=1.3.2
- shap>=0.48.0
- seaborn>=0.13.2
- matplotlib>=3.10.3 