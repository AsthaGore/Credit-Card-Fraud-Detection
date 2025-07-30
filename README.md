# Credit Card Fraud Detection

This project is a machine learning-based approach to detect fraudulent credit card transactions using a dataset that has undergone PCA (Principal Component Analysis) transformation. The model was built and evaluated in Google Colab.

#Project Overview

This notebook tackles a binary classification task to detect fraud in credit card transactions. The dataset is highly imbalanced and includes:

* V1 to V28: Principal components (from PCA).
* Time: Seconds since the first transaction.
* Amount: Transaction amount.
* Class: Target variable (1 = fraud, 0 = not fraud).

Due to confidentiality, the original features are anonymized using PCA.

#Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Size: 284,807 transactions
- Fraud cases: ~0.17% of the data (highly imbalanced)

#Project Highlights

- Data Preprocessing and EDA
- Handling Imbalanced Dataset
- Model Training and Evaluation
- Confusion Matrix, Precision, Recall, F1-score

Model Used: 'Random Forest Classifier'
--Why Random Forest?

1.Better Accuracy & Performance: It generally provides high accuracy by combining multiple decision trees (ensemble learning).

2.Handles Imbalanced Data Well: With techniques like class weighting and sampling, it performs effectively even when fraud cases are rare.

3.Robust & Reliable: Resistant to overfitting compared to single decision trees.

Random Forest serves as a strong baseline model for binary classification problems like fraud detection, especially when interpretability, stability, and class imbalance handling are important
  
## 🚀 How to Run

1. Open the [Colab Notebook](./CreditCardFraudDetection.ipynb).
2. Upload the dataset (creditcard.csv) or mount from Google Drive.
3. Run each cell sequentially.
