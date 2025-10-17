# Credit Card Fraud Detection System
A production-ready machine learning system for detecting fraudulent credit card transactions using ensemble methods, achieving 88% recall with 91% precision on highly imbalanced European transaction data.

## Methodology
1) Data Loading & Preprocessing
2) Exploratory Data Analysis (Visualisations & Statistical Tests)
3) Feature Engineering
4) Class Imbalance Treatment Strategies (Sampling)
5) Supervised Learning Models
6) Business Analytics
7) Conclusion & Next Steps

## Key Results

- ROC-AUC: 0.978
- Precision: 91% (only 9 false positives per 56,962 transactions)
- Recall: 88% (catches 86 of 98 fraud cases)
- Business Impact: Prevents €10,510 in fraud at €1,425 investigation cost

## Dataset
Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- 284,807 transactions from European cardholders
- 492 frauds (0.17% of all transactions)
- 28 PCA-transformed features (V1-V28) + Time + Amount
- Highly imbalanced classification problem

## Technical Stack
Core Libraries:
- Python 3.8+
- pandas 1.5.3
- numpy 1.26.4
- scikit-learn 1.3.2
- xgboost 2.0.3
- imbalanced-learn 0.11.0

Visualisation:
- matplotlib 3.7.1
- seaborn 0.12.2
- plotly 5.14.1

## License
This project is licensed under the MIT License.
