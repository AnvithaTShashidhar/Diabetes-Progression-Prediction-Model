# 🩺 Diabetes Progression Prediction Model

Diabetes progression is influenced by several physiological and biochemical factors.
This project explores the Diabetes dataset from the Scikit-Learn library to understand which clinical features contribute most to disease progression and to build a model that predicts a patient’s progression score.

The dataset contains 10 baseline variables such as age, BMI, blood pressure, and serum measurements.

This project aims to:

Determine factors that significantly affect diabetes progression,

Interpret how these factors influence disease severity,

Use these factors to predict diabetes progression scores.

# ⚙️ Methodology
Skills & Concepts Used:

Python | Statistics | Regression Models | Feature Engineering

I used Python to analyze this dataset, and Jupyter Notebook as my environment.
The libraries used were:
pandas, numpy, matplotlib, seaborn, statistics, scipy, and various models from sklearn.

The workflow included:

Loading and exploring the dataset,

Visualizing important relationships,

Engineering interaction features (such as BMI × Blood Pressure),

Training multiple regression models (Ridge, Lasso, ElasticNet, Random Forest, Gradient Boosting),

Selecting the best-performing model based on evaluation metrics.

# 📊 Results

I found that the most influential clinical features affecting diabetes progression were:

BMI — the strongest predictor of disease progression,

Blood Pressure,

Serum measurements such as s1 and s5,

Interaction features, especially bmi × blood pressure and age × bmi.

Higher BMI and certain serum marker levels were associated with increased progression scores.
Engineered features significantly improved the predictive ability of the models.

The final model was found to predict the progression score fairly well, achieving strong R² performance and relatively low error metrics after feature engineering.


