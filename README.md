### Insurance Premium Prediction and Model Diagnostics
- This project involves building a **Multiple Linear Regression Model (MLRM)** to predict individual insurance charges based on demographic and lifestyle characteristics. The analysis emphasizes **model selection, diagnostic testing, and validation** to ensure statistical robustness and adherence to classical regression assumptions.
---
## Objective
To develop a regression model that accurately estimates insurance premiums (charges) using the following predictors:
- Age  
- Sex  
- Body Mass Index (BMI)  
- Smoking status  
- Number of children  
- Region  
---
## Goals
- Understand the relationship between insurance charges and explanatory variables.  
- Identify the most influential factors affecting insurance costs.  
- Evaluate model performance using rigorous diagnostic tools.  
- Ensure compliance with the key assumptions of linear regression.  
---
## Methodology
### Exploratory Data Analysis (EDA)
- Summary statistics  
- Correlation matrix  
- Visualization of variable relationships  
---
### Model Building
- Estimation of a full Multiple Linear Regression Model using **statsmodels**  
- Cross-validation to assess out-of-sample generalization  
---
### Model Diagnostics
- **Multicollinearity:** Variance Inflation Factor (VIF)  
- **Residual normality:** Shapiro–Wilk test, Q–Q plots  
- **Homoscedasticity:** Breusch–Pagan test  
- **Autocorrelation:** Durbin–Watson statistic  
- **Influential observations:** Cook’s distance, leverage plots  
---
###  Model Validation
- 20-fold cross-validation  
- Performance evaluation using:
  - Adjusted R-squared  
  - Root Mean Squared Error (RMSE)  
---
## Key Tools & Libraries
- **Python:** pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Econometrics:** statsmodels  
- **Model validation:** scikit-learn  
- **Statistical testing:** SciPy  
---
## Project Focus
This project emphasizes **statistical rigor, model diagnostics, and interpretability** rather than purely predictive performance making it suitable as an applied econometrics and statistical modeling portfolio project.
