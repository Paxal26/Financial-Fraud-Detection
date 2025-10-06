# UPI Fraud Detection

**Project Type:** Machine Learning / Cybersecurity  
**Language:** Python (Flask, XGBoost, Logistic Regression)  

---

## Overview
This project detects fraudulent UPI transactions using machine learning. It leverages XGBoost and Logistic Regression models trained on transaction data to accurately identify both fraud and non-fraud transactions.

The project includes:  
- Real-time prediction through a Flask web app  
- Data preprocessing and feature engineering  
- Handling of categorical variables using Label Encoding  
- Visualization and logging for monitoring transaction patterns  

---

## Features
- **Fraud Detection:** Accurately predicts fraudulent transactions in real-time.  
- **Interactive Web App:** Users can input transaction data via a Flask interface.  
- **Dropdown Support:** Select transaction type from a dropdown menu.  
- **Secure Handling:** `.env` files are ignored; sensitive API keys are not stored in the repo.  
- **Visualization:** Graphs and logs for analyzing transaction patterns.  

---

## Requirements
- Python 3.9+  
- Flask  
- pandas, numpy, scikit-learn, xgboost  
- Optional: matplotlib, seaborn for visualization  

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Paxal26/Financial-Fraud-Detection.git
cd Financial-Fraud-Detection
