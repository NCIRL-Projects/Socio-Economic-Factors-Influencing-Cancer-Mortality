# Socio-Economic Factors Influencing Cancer Mortality

## Project Overview
This project investigates the socio-economic factors influencing cancer mortality rates in the US using a Multiple Linear Regression (MLR) model. The aim is to identify significant predictors of cancer mortality and use these insights to inform cancer prevention strategies and improve early detection efforts.

## Introduction
We utilize Multiple Linear Regression to analyze the relationship between cancer mortality (dependent variable) and various socio-economic factors (independent variables). The regression model helps in identifying the most impactful predictors and understanding their effects on cancer mortality.

### Multiple Linear Regression Formula
The formula for Multiple Linear Regression is:

\[ y = b0 + b1x1 + b2x2 + \... + bnxn + \epsilon \]

Where:
- `y` is the dependent variable (cancer mortality rate),
- `x1`, `x2`, ..., `xn` are independent variables,
- `b1`, `b2`, ..., `bn` are coefficients representing the effect of each independent variable,
- `b0` is the intercept, and
- `\epsilon` is the error term.

## Assumptions
Multiple Linear Regression relies on several key assumptions:
- **Linearity**: The relationship between dependent and independent variables is linear.
- **Independence**: Observations are independent of each other.
- **Normality**: Residuals are normally distributed.
- **Homoscedasticity**: Constant variance of residuals across all levels of the independent variables.
- **No Multicollinearity**: Independent variables are not highly correlated.

Diagnostics and tests to validate these assumptions include:
- Scatter plots
- Durbin-Watson test
- Cook's distance
- Normality test
- Variance Inflation Factor (VIF)
- Residuals vs. Fitted Plot

## Exploratory Data Analysis (EDA)

### Data Description
The dataset includes cancer mortality data for 3000+ US counties with 25 variables, such as:
- Death rate
- Incidence rate
- Median income
- Poverty percent
- Median age
- Education levels
- Employment rates
- Health coverage types
- Racial demographics

### Data Exploration
- **Population Filtering**: Eliminated counties with populations below 10,000 to improve data validity.
- **Missing Values**: Checked for and confirmed the absence of missing values.

### Visualizations and Correlations
- **Histograms**: Examined distributions of variables and transformed them to improve linearity and normality.
- **Scatterplot Matrix & Heatmap**: Identified relationships and potential multicollinearity among variables.

## Model Building and Evaluation

### Initial Model
- Built a baseline MLR model with all independent variables.
- Evaluated residuals, coefficients, and p-values to assess model fit.

### Model Improvement
- **Transformed Variables**: Added transformed variables to address issues identified in EDA.
- **Variable Selection**: Included only statistically significant variables to refine the model.

### Diagnostics and Validation
- **Adjusted R²**: Improved to 57.38%, indicating better model fit.
- **Residuals vs. Fitted Plot**: Checked for randomness in residuals.
- **Normal Q-Q Plot**: Verified normal distribution of residuals.
- **Scale-Location Plot**: Confirmed constant variance of residuals.
- **Residuals vs. Leverage Plot**: Identified potential influential observations.

### Cooks Distance Test
- Assessed influence of observations on regression coefficients.
- Investigated high Cooks distance values for potential outliers.

## Model Summary
- **Final Model R²**: 0.6011, indicating a good fit.
- **Significance**: Coefficients have p-values < 0.05, showing strong relationships with the dependent variable.

## Mortality Rate Model
- Applied model to calculate the "Mortality Rate" as the ratio of death rate to incidence rate.
- **Model R²**: 0.5207, showing the proportion of variance explained by the predictors.

## Conclusion
The MLR model provides valuable insights into socio-economic factors affecting cancer mortality. The analysis highlights significant predictors and underscores the importance of addressing socio-economic disparities in healthcare.

## Future Work
- **Dataset Expansion**: Acquire more diverse and comprehensive data.
- **Model Enhancement**: Explore alternative models and methods to improve accuracy.
- **Practical Applications**: Integrate findings into policy-making and cancer prevention strategies.

## Contact
Aleksandra Kalisz  
Postgraduate Diploma in Science in Data Analytics  
National College of Ireland, Dublin, Ireland  
alexkalisz@gmail.com
