# Diabetes Prediction using Decision Tree Regressor

## Project Overview

This project uses Machine Learning to predict diabetes progression using the Diabetes dataset from Scikit-Learn.

A Decision Tree Regressor model is trained on medical features such as:

- Age
- Sex
- BMI
- Blood Pressure
- S1 to S6 health measurements

The model predicts a continuous diabetes progression score.

---

## Dataset

Dataset source:

```python
from sklearn.datasets import load_diabetes
```

Number of features: 10

Target Variable:

- Diabetes disease progression measure

Features:

- age
- sex
- bmi
- bp
- s1
- s2
- s3
- s4
- s5
- s6

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Machine Learning Workflow

1. Load Diabetes Dataset
2. Data Exploration
3. Correlation Analysis
4. Train-Test Split
5. Decision Tree Regressor Model
6. Hyperparameter Tuning using GridSearchCV
7. Model Evaluation

Metrics Used:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## Model Performance

Example Results:

R² Score: 0.38

MAE: 51.63

MSE: 3852.777