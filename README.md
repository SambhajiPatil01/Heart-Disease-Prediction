# Heart-Disease-Prediction
This project predicts heart disease using patient medical data. It analyzes factors like age, cholesterol, blood pressure, chest pain, and exercise-induced angina. Models such as Random Forest and XGBoost give the best results, supporting early detection and prevention.

## Dataset
The dataset contains patient health records with attributes such as age, sex, chest pain type, blood pressure, cholesterol, blood sugar, ECG results, maximum heart rate, exercise-induced angina, ST depression, and thalassemia. The target indicates presence or absence of heart disease.

## Key Insights
- Risk of heart disease increases with age, and men are more likely to be affected
- Chest pain type is one of the strongest predictors
- High cholesterol and high blood pressure are associated with higher risk
- Patients with exercise-induced angina or low maximum heart rate tend to show more signs of disease
- ST depression (oldpeak) is an important clinical indicator

## Machine Learning Models
- We applied different algorithms to predict heart disease:
- Logistic Regression → Simple and interpretable baseline model
- Random Forest → High accuracy and useful for feature importance analysis
- XGBoost / Gradient Boosting → Best overall performance for prediction
- Support Vector Machine (SVM) → Works well with smaller datasets when tuned properly

## Best Algorithm:
- XGBoost and Random Forest give the most accurate predictions
- Logistic Regression is useful in medical applications where interpretability is important
