# 🚢 Titanic Survival Prediction

Predicting whether a passenger survived the Titanic disaster using classic Machine Learning models with **Scikit-learn**.

---

## 📌 Overview

The Titanic dataset is one of the most popular beginner ML datasets. The goal is to predict survival (`0 = No`, `1 = Yes`) based on passenger details like age, sex, class, and fare.

This notebook covers the full ML workflow — from raw data to predictions.

---

## 🔄 Workflow

```
Load Data → EDA → Preprocess → Split → Train → Evaluate → Predict
```

---

## 📊 Models Used

| Model | Accuracy |
|---|---|
| Logistic Regression | ~80% |
| Random Forest | ~82% |

> Random Forest is used as the final model for evaluation and prediction.

---

## 📁 Files

```
01_titanic/
├── Titanic.ipynb    # Main notebook
├── titanic.csv      # Dataset
└── README.md        # This file
```

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data loading & manipulation
- **NumPy** — numerical operations
- **Matplotlib / Seaborn** — visualizations
- **Scikit-learn** — ML models & evaluation

---

## 📈 What's Inside the Notebook

1. **Load Data** — read CSV, check shape
2. **EDA** — survival by sex, class, age distribution plots
3. **Preprocess** — drop irrelevant columns, encode categories, fill nulls
4. **Split** — 80/20 train-test split
5. **Train** — Logistic Regression vs Random Forest
6. **Evaluate** — classification report + confusion matrix heatmap
7. **Feature Importance** — which features impact survival most
8. **Predict** — predict survival on new sample passengers

---

## 🔑 Key Learnings

- **Data preprocessing** is the most critical step in any ML pipeline
- **Sex** and **Pclass** are the strongest predictors of survival
- Random Forest outperforms Logistic Regression on this dataset
- Always compare multiple models before choosing the best one

---

## 📂 Dataset

[Titanic Dataset — Kaggle](https://www.kaggle.com/competitions/titanic)

---

## 🚀 How to Run

1. Open `Titanic.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Upload `titanic.csv` to the Colab session
3. Run all cells top to bottom (`Runtime → Run all`)