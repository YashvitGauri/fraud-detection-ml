# Fraud Detection System using Machine Learning

This project is an end-to-end machine learning application that predicts whether a financial transaction is fraudulent or not.

The trained model file is not included due to GitHub size limits.  
You can train the model using `analysis_model.ipynb`.

## Features
- Machine learning pipeline with preprocessing and classification
- Real-time prediction using a Streamlit web app
- User-friendly UI for entering transaction details

## Tech Stack
- Python
- Scikit-learn
- Pandas
- Streamlit
- Joblib

## Dataset
The dataset used for training is not included due to size limitations.
You can use any standard fraud detection dataset or your own transaction data
to retrain the model using `analysis_model.ipynb`.
->Data Source: Kaggle:- Fraud Detection Dataset by Aman Ali Siddiqui 


## How to Run
1. Clone the repository
2. Install dependencies:
    pip install -r requirements.txt
3. Run the Streamlit app:
    streamlit run fraud_detection.py

## Input Parameters
- Transaction Type
- Amount
- Sender and Receiver balances

## Output
- Fraud or Non-Fraud prediction