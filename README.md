# ⚡ EV vs Petrol Prediction

A machine learning project analyzing global EV adoption trends (2010–2025) and predicting EV market dominance using Logistic Regression and Random Forest.

## 📁 Files
- `ev-petrol-prediction.ipynb` — Main notebook (EDA + ML)
- `ev_vs_petrol_dataset_v3.csv` — Raw dataset
- `ev_petrol_prediction_dataset_cleaned.csv` — Cleaned dataset
- `dashboard.pbix` — Power BI dashboard

## 📊 Dataset
- 1,200 rows, 22 features
- Covers 10 countries across 5 regions
- Target variable: `is_ev_dominant` (binary classification)

## 🤖 Models

| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 97.2% | 0.49 |
| Random Forest | 98.3% | 0.66 |

## 🛠️ Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Power BI
