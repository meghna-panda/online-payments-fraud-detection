# 🛡️ Online Payments Fraud Detection with Machine Learning

This project demonstrates how to build a machine learning model using Python to detect fraudulent online payment transactions. It uses a Decision Tree Classifier trained on a dataset of transaction history to classify transactions as **Fraud** or **No Fraud**.

---

## 📂 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🧠 Machine Learning Approach](#-machine-learning-approach)
- [📊 Dataset Information](#-dataset-information)
- [📈 Model Performance](#-model-performance)
- [📌 Project Structure](#-project-structure)
- [🙋‍♂️ Contributing](#-contributing)

---

## 📌 Project Overview

Online payment systems have simplified transactions but also increased the risk of fraud. This project develops a machine learning system to **detect and prevent online payment frauds** using historical transaction data.

---

## 🧠 Machine Learning Approach

We use a **Decision Tree Classifier** to detect fraudulent transactions based on key features in the dataset.

### 🧪 Steps Followed:

1. Load and inspect data
2. Clean and preprocess features
3. Encode categorical values
4. Split data into training and test sets
5. Train a classification model
6. Make predictions and evaluate performance

---

## 📊 Dataset Information

The dataset used is from **Kaggle** and includes anonymized transaction data.

| Column Name       | Description |
|-------------------|-------------|
| `step`            | Time step (1 step = 1 hour) |
| `type`            | Type of transaction (CASH_OUT, PAYMENT, etc.) |
| `amount`          | Amount of the transaction |
| `nameOrig`        | Customer initiating the transaction |
| `oldbalanceOrg`   | Balance of sender before transaction |
| `newbalanceOrig`  | Balance of sender after transaction |
| `nameDest`        | Recipient of the transaction |
| `oldbalanceDest`  | Balance of recipient before transaction |
| `newbalanceDest`  | Balance of recipient after transaction |
| `isFraud`         | 1 = Fraud, 0 = No Fraud |
| `isFlaggedFraud`  | Flag by system as potentially fraudulent |

✅ No missing values.

---

### 📦 Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- plotly (for visualization)

##📈 Model Performance

Model Used: Decision Tree Classifier

Accuracy: 99.93%

## Project Structure
📁 online-payment-fraud-detection/
├── credit_card.csv           # Dataset file
├── fraud_detection.py        # Main ML script
└── README.md                 # Documentation

## 🙋‍♂️ Contributing
Contributions, ideas, and feedback are welcome!
Fork the repo
Create a new branch (git checkout -b feature-name)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature-name)
Create a Pull Request ✅

