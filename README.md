### Insurance Premium Prediction and Model Diagnostics
* This project involves building a Multiple Linear Regression Model (MLRM) to predict individual insurance charges based on several demographic and lifestyle factors. The project emphasizes model selection, 
* diagnostics, and validation techniques to ensure the robustness of results.

🔍 Objective
##### To develop a regression model that accurately estimates the insurance premium (charges) using predictors such as:
* Age
* Sex
* Body Mass Index (BMI)
* Smoking status
* Number of children
* Region
🎯 Goals
* Understand the relationship between insurance charges and predictors.
* Identify the most influential variables affecting the cost of insurance.
* Evaluate model performance using multiple diagnostic tools.
* Ensure the model meets the key assumptions of linear regression.
🧪 Methodology
1. Exploratory Data Analysis (EDA)
* Summary statistics
* Correlation matrix
* Visualization of relationships
3. Model Building
* Fitting a full MLRM using Statsmodels
* Cross-validation to assess model generalization
4. Model Diagnostics
* Multicollinearity: Variance Inflation Factor (VIF)
* Residual Normality: Shapiro-Wilk Test, QQ Plots
* Homoscedasticity: Breusch-Pagan Test
* Autocorrelation: Durbin-Watson Statistic
* Influential Observations: Cook’s Distance, Leverage Plots
5. Model Validation
* 20-fold Cross-Validation
* Adjusted R-squared and RMSE evaluation
📊 Key Tools & Libraries
* Python (Pandas, NumPy, Matplotlib, Seaborn)
* statsmodels for regression and diagnostics
* scikit-learn for cross-validation
scipy for statistical tests
