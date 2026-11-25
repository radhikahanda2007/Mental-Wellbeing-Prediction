# 🧠 Mental Well-being Score Prediction System

A Supervised Machine Learning Regression project that predicts a student's Mental Well-being Score (on a scale of 10–100) based on daily lifestyle habits such as sleep duration, screen time, study hours, physical activity, and social interaction.

## 📂 Repository Contents
- `Mental_Wellbeing.ipynb` — Complete Google Colab notebook (EDA, T-test, Preprocessing, Model Training, Hyperparameter Tuning, and Live Interactive UI)
- `mental_wellbeing.csv` — Dataset containing 500 student lifestyle records and 8 attributes
- `wellbeing_model.pkl` — Serialized final Ridge Regression pipeline tuned via 5-Fold GridSearchCV

## 📊 Key Results
- **Best Model:** Ridge Regression (with `StandardScaler` + `OneHotEncoder` Pipeline)
- **R² Score:** ~0.89
- **Hypothesis Testing:** Independent two-sample t-test ($p < 0.0001$) confirmed that regular physical activity significantly improves well-being scores.
