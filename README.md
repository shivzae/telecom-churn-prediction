# telecom-churn-prediction

This machine learning project predicts customer churn in a telecom dataset using classification algorithms. The goal is to help telecom providers identify at-risk customers before they leave.

---

## 📁 Dataset

- `churntelco.csv`: Includes customer account information, service usage, and whether they have churned.
- Key features include: `Contract`, `Tenure`, `MonthlyCharges`, `InternetService`, and more.

---

## 🔍 Problem Statement

Customer churn is a major concern in the telecom industry. This project aims to build models that predict churn based on customer behavior and demographics using supervised learning.

---

## 🧠 Models Trained

- Decision Tree
- XGBoost
- **Random Forest** ✅ *(Best performance)*

---

## 🧪 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🎯 Results

| Model          | Mean Accuracy | Std Dev |
|----------------|---------------|---------|
| Random Forest  | **84.10%**     | 0.068   |
| XGBoost        | 83.48%         | 0.078   |
| Decision Tree  | 78.05%         | 0.066   |

> Random Forest showed the best performance overall.

---

## 🚀 Getting Started

Install requirements:

```bash
pip install -r requirements.txt
```

Run the notebook:
```bash
jupyter notebook telecom_churn_prediction.ipynb
```
