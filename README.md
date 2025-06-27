LINEAR & LOGISTIC REGRESSION – NOTES & EXERCISES

This repository includes exercises about Linear Regression and Logistic Regression. It follows a structured journey from simple linear models to more complex techniques including regularization and classification. 

------------------------------------------------------------
PART 1: EXPLORING SIMPLE LINEAR REGRESSION
------------------------------------------------------------

- Investigated relationships between two variables using scatterplots and trendlines.
- Modeled bivariate relationships using the basic equation:  
  y = b₀ + b₁x
- Interpreted the slope (b₁) as the change in y for each unit increase in x.
- Studied residuals (errors) to understand the gap between predicted and actual values.
- Gained hands-on intuition for fitting lines and recognizing patterns in noisy data.

------------------------------------------------------------
PART 2: BUILDING AND EVALUATING LINEAR MODELS
------------------------------------------------------------

- Practiced fitting linear models using least squares estimation.
- Measured model performance with R-SQUARED, representing the proportion of variance in y explained by the model.
- Applied ADJUSTED R-SQUARED to compare models with different numbers of predictors.
- Reviewed key modeling assumptions:
  - Linear relationship between variables
  - Independence of residuals
  - Constant variance (homoscedasticity)
  - Normally distributed residuals

------------------------------------------------------------
PART 3: INFERENCE IN LINEAR REGRESSION
------------------------------------------------------------

- Conducted hypothesis testing for regression coefficients using p-values.
- Understood that a low p-value suggests a statistically significant relationship between predictor and response.
- Analyzed confidence intervals to assess the range of plausible slope values.
- Used the F-STATISTIC to test the overall significance of the model.
- Practiced making predictions with interval estimates to account for uncertainty.

------------------------------------------------------------
PART 4: EXPANDING TO MULTIPLE PREDICTORS AND NONLINEAR EFFECTS
------------------------------------------------------------

- Built MULTIPLE LINEAR REGRESSION (MLR) models with two or more predictors.
- Explored INTERACTION TERMS (e.g., x₁ * x₂) to capture combined effects of predictors.
- Applied transformations (e.g., log, square) to handle curvature and nonlinearity.
- Used INDICATOR VARIABLES to include categorical features.
- Detected and managed MULTICOLLINEARITY using VARIANCE INFLATION FACTOR (VIF).

------------------------------------------------------------
PART 5: INFERENCE IN MULTIPLE LINEAR REGRESSION
------------------------------------------------------------

- Extended statistical inference techniques to models with multiple variables.
- Interpreted coefficients in the presence of other variables.
- Evaluated the significance of each predictor while adjusting for others.
- Reinforced the importance of checking assumptions even in complex models.

------------------------------------------------------------
PART 6: MODEL SELECTION AND REGULARIZATION
------------------------------------------------------------

- Compared models using AIC (Akaike Information Criterion) and BIC to balance fit and simplicity.
- Practiced selecting models with fewer predictors that still generalize well.
- Studied the BIAS-VARIANCE TRADEOFF in model performance.
- Implemented REGULARIZATION METHODS:
  - RIDGE REGRESSION (L2 penalty): Shrinks coefficients toward zero but doesn’t eliminate them.
  - LASSO REGRESSION (L1 penalty): Can reduce coefficients to exactly zero for feature selection.
  - ELASTIC NET: Combines L1 and L2 to balance shrinkage and selection.

------------------------------------------------------------
PART 7: CLASSIFICATION WITH LOGISTIC REGRESSION
------------------------------------------------------------

- Shifted from predicting continuous outcomes to binary classification problems.
- Modeled log-odds using the logit equation:  
  log(p / (1 - p)) = β₀ + β₁x₁ + ... + βₖxₖ
- Used the SIGMOID FUNCTION to convert log-odds into probabilities.
- Interpreted model coefficients in terms of how they influence the odds of an event.
- Evaluated classifier performance using:
  - CONFUSION MATRIX
  - PRECISION and RECALL
  - F1-SCORE (especially valuable in imbalanced datasets)

------------------------------------------------------------
PART 8: FOREST FIRES DATA ANALYSIS
------------------------------------------------------------

DATA:

This collection of regression exercises was built primarily using the CALIFORNIA HOUSING dataset, exploring relationships between housing prices and factors such as median income, house age, and population density. These exercises provided a hands-on foundation in SIMPLE and MULTIPLE LINEAR REGRESSION, MODEL DIAGNOSTICS, INFERENCE, and REGULARIZATION TECHNIQUES (Ridge, Lasso, Elastic Net).

The final project applied these concepts to a real-world classification problem using the FOREST FIRES dataset from Portugal. The goal was to model the likelihood of fire occurrence based on environmental conditions such as temperature, humidity, wind, and dryness indexes (DMC, DC, FFMC).

Forest Fires dataset source:  
https://archive.ics.uci.edu/ml/datasets/forest+fires
