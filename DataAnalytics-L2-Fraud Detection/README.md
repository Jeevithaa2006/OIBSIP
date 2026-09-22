# Fraud Detection

## Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning. The main challenge is the highly imbalanced dataset.

## Objectives

- Analyse fraudulent and non-fraudulent transactions
- Understand class imbalance
- Perform EDA on transaction amount and time
- Handle imbalance using SMOTE
- Train machine learning models
- Evaluate Precision, Recall, F1-Score and AUC-ROC
- Analyse important features

## Dataset

The project uses the Credit Card Fraud Detection dataset.

- Total transactions: 284,807
- Fraudulent transactions: 492
- Non-fraudulent transactions: 284,315

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## Methodology

### 1. Data Loading
The dataset is loaded using Pandas.

### 2. Data Analysis
Fraud and non-fraud transactions are analysed using transaction amount and time visualizations.

### 3. Class Imbalance
The dataset is highly imbalanced, so accuracy alone can be misleading.

### 4. Data Splitting
The data is divided into training and testing sets using stratification.

### 5. SMOTE
SMOTE is applied to handle class imbalance.

### 6. Model Training
Two models are trained:

- Logistic Regression
- Decision Tree

### 7. Model Evaluation
Models are evaluated using:

- Precision
- Recall
- F1-Score
- AUC-ROC Curve

### 8. Feature Analysis
Important features contributing to fraud detection are analysed.

## Key Insights

- Fraudulent transactions form a very small percentage of the dataset.
- Class imbalance is an important challenge.
- Recall helps detect more fraudulent transactions.
- Precision helps reduce false fraud alerts.

## Conclusion

Machine learning can be used to identify potentially fraudulent transactions. Handling class imbalance and using suitable evaluation metrics are important for fraud detection.

## Project Files

- `Fraud_Detection.ipynb` – Complete analysis
- `README.md` – Project documentation
- `Screenshots` – Important visualizations

## Author

Jeevitha

## Internship

Oasis Infobyte (OIBSIP) – Data Analytics Internship
