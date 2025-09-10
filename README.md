
# Credit Card Fraud Detection

## Overview
This project applies machine learning algorithms to detect fraudulent credit card transactions, helping to safeguard financial systems and customers from losses. It features data analysis, preprocessing, model building, evaluation, and comparison to distinguish fraud effectively in transaction datasets.

## Features
- Exploratory data analysis of transaction patterns.
- Handles dataset imbalance (using techniques like undersampling or SMOTE).
- Implements multiple algorithms (e.g., Logistic Regression, Decision Trees, SVM, KNN, Naive Bayes).
- Model selection based on evaluation metrics (accuracy, recall, precision, F1-score).
- Clean, reproducible code suitable for experimentation and extension.

## Installation

```bash
git clone https://github.com/soumyakaruturi/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
pip install -r requirements.txt
```
*Requires Python 3.x and pip.*

## Usage

1. Download and place the dataset in the `data/` folder (commonly sourced from Kaggle).
2. Start analysis and training:
   ```bash
   python main.py
   ```
3. View model performance output for detecting fraud.

## Data Source

- Typically uses the "Credit Card Fraud Detection" dataset from Kaggle.
- Anonymized data with 31 features, thousands of transactions, and a binary `Class` label (1 for fraud, 0 for normal).

## Modeling Process

- Data exploration, visualization
- Feature scaling and transformation
- Model training and testing
- Imbalanced data mitigation
- Evaluation and comparison of algorithms

## Sample Algorithms

- Logistic Regression
- Decision Trees
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Deep Learning (optional for advanced users)

## Results

Include plots of confusion matrix, performance metrics (e.g., accuracy, precision, recall), and sample predictions from various algorithms.

