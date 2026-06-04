# Telco Customer Churn Prediction 

---

## File Structure

```
telco-churn-prediction/
├── 23F-0713_A-05.ipynb                      # Main Jupyter Notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv     # Dataset
└── README.md
```

---

## Assignment Overview

A classification-based machine learning project to predict customer churn using the Telco Customer Churn dataset (7,043 records).

| Part | Topic |
|------|-------|
| 1 | Data preprocessing & feature engineering |
| 2 | Baseline modeling with Logistic Regression |
| 3 | Decision Trees & overfitting analysis |
| 4 | Ensemble learning — Random Forest (Bagging) & XGBoost (Boosting) |
| 5 | Model evaluation & comparison (Accuracy, Precision, Recall, F1, ROC-AUC) |

---

## Libraries Used

- `pandas` / `numpy` – Data manipulation
- `matplotlib` / `seaborn` – Visualization
- `sklearn` – Preprocessing, classification models, evaluation metrics
- `xgboost` – XGBoost classifier

---

## How to Run

1. Clone the repository:
```bash
   git clone https://github.com/KainatZahraa/telco-churn-prediction.git
   cd telco-churn-prediction
```

2. Install dependencies:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

3. Launch Jupyter Notebook:
```bash
   jupyter notebook 23F-0713_A-05.ipynb
```

> Make sure `WA_Fn-UseC_-Telco-Customer-Churn.csv` is in the same directory as the notebook.
