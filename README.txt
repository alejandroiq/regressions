Forest Fire Prediction: Regression and Classification Modeling
This project applies statistical modeling techniques to predict forest fire behavior using meteorological and fuel moisture data. It includes both regression (predicting log-transformed burned area) and binary classification (high vs. low fire severity) approaches.

📁 Contents
Step 1–2: EDA and Data Preparation

Step 3–4: Baseline and Interaction Regression Models

Step 5: Regularization using Ridge and Lasso

Step 6–7: Binary Classification with Logistic Regression

Step 8: Assumptions (VIF, Normality, Outliers)

Step 9: Final Insights and Model Recommendations

📊 Models Evaluated
OLS Regression Models: Baseline, Interaction, Minimal

Regularization: Ridge and Lasso

Classification: Logistic Regression using DMC, wind, and temp:DMC

🔍 Key Insights
Wind and the interaction between temperature and DMC are consistent drivers of fire area.

Ridge regression outperformed Lasso across models.

Logistic regression achieved ~62% accuracy with solid precision and recall using only three predictors.

📦 Requirements
Python 3.8+

pandas, numpy, scikit-learn, statsmodels, matplotlib, seaborn

📌 Dataset
UCI Forest Fires Dataset
https://archive.ics.uci.edu/ml/datasets/forest+fires