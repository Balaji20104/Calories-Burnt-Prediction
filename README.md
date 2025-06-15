# 🔥 Calories Burnt Prediction Using Machine Learning

This project uses user activity data (age, gender, weight, height, duration, heart rate, etc.) to **predict the number of calories burnt** using an XGBoost regression model.

---

## 📁 Files Included

- `Untitled5.ipynb` – Jupyter notebook with full code and visualization
- `calories.csv` – Target dataset (calories burnt)
- `exercise.csv` – Input dataset (activity features)

---

## 🛠 Tools & Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- XGBoost
- Scikit-learn

---

## 📊 Model Summary

- **Algorithm**: XGBoost Regressor
- **Train/Test Split**: 80/20
- **Evaluation Metric**: R² Score

### ✅ Model Accuracy

| Dataset       | R² Score |
|---------------|----------|
| Training Set  | 0.99+    |
| Testing Set   | ~0.95    |

> The model performs extremely well on both training and test data, showing strong generalization.

---

## 🚀 How to Run

1. Clone the repo or download the notebook
2. Install required libraries (if not already installed):
   ```bash
   pip install xgboost pandas seaborn scikit-learn matplotlib
