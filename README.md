# fraud-credit-card
# Credit Card Fraud Detection System

A machine learning project that detects fraudulent credit card transactions using Logistic Regression. This project demonstrates practical application of data science techniques for financial security.

## 📊 Project Overview

This project addresses the critical challenge of credit card fraud detection by building a binary classification model. The system analyzes transaction patterns to distinguish between legitimate and fraudulent activities with high accuracy.

## 📈 Key Features

- **Data Preprocessing**: Handles highly imbalanced dataset using undersampling techniques
- **Model Training**: Implements Logistic Regression for binary classification
- **Performance Evaluation**: Achieves 90.8% accuracy on test data
- **Feature Engineering**: Utilizes PCA-transformed features for optimal performance

## 🛠️ Technical Implementation

### Data Characteristics
- **Dataset**: 284,807 transactions (492 fraudulent, 284,315 legitimate)
- **Features**: 30 numerical features (PCA-transformed for confidentiality)
- **Target**: Binary classification (0 = Legitimate, 1 = Fraudulent)

### Methodology
1. **Data Analysis**: Explored dataset imbalance and feature distributions
2. **Data Balancing**: Applied undersampling to create balanced dataset (492 each class)
3. **Model Training**: Used Logistic Regression with 80-20 train-test split
4. **Evaluation**: Assessed model performance using accuracy metrics

### Model Performance
- **Training Accuracy**: 92.5%
- **Testing Accuracy**: 90.8%

## 🚀 Installation & Usage

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required libraries (see requirements.txt)

### Installation
```bash
# Navigate to project directory
cd credit-card-fraud-detection

# Install dependencies
pip install -r requirements.txt
# Start Jupyter Notebook
jupyter notebook

# Open and run credit_card_fraud_detection.ipynb
numpy==1.21.0
pandas==1.3.0
scikit-learn==0.24.2
matplotlib==3.4.2
seaborn==0.11.1
jupyter==1.0.0




This is Credit card fraud detection project using Machine Learning in Python.

Dataset link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
