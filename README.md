# 💳 Credit Card Fraud Detection Using Autoencoders

## 1. Overview

This project utilizes an **Autoencoder (a type of neural network)** to detect fraudulent credit card transactions. The model learns the normal transaction patterns and identifies anomalies based on **reconstruction error**. Transactions with high reconstruction errors are flagged as potential fraud.

## 2. Features

- 📌 **Preprocessing:** Standardizes transaction data for better model performance.
- 🤖 **Autoencoder Model:** Learns to reconstruct normal transactions.
- 📊 **Fraud Detection:** Identifies anomalies using reconstruction error.
- 📉 **Threshold-based classification:** Flags transactions with high error as fraud.
- 🔍 **Evaluation:** Analyzes fraudulent transactions with a set threshold.

## 3. Tech Stack

- **Python**
- **Pandas** & **NumPy**
- **Scikit-Learn**
- **TensorFlow / Keras**
- **Matplotlib & Seaborn** (for visualization)

## 4. Dataset

The project uses the **[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)** from Kaggle. It contains anonymized transaction details, where the goal is to distinguish between fraudulent and legitimate transactions.

## 5. Results & Findings

- The autoencoder successfully learned the patterns of normal transactions.
- Transactions with high **reconstruction error** were identified as fraudulent.
- A threshold-based approach was used to classify outliers as potential fraud cases.

## 6. Future Enhancements

- Implement an **adaptive thresholding** technique for better fraud detection.
- Use **deep learning models (LSTM, CNNs)** for sequential transaction analysis.
- Deploy the model into a **real-time fraud detection system** with Flask or FastAPI.

