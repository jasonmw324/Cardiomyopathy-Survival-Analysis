# Cardiomyopathy-Survival-Analysis


## Project Overview

This project examines clinical, lifestyle, and body characteristics associated with survival among patients diagnosed with cardiomyopathy. The analysis uses Cox proportional hazards models to identify predictors of time-to-death and compare model performance. 
- **The report with all analyses can be found [here](./Cardiomyopathy-Survival-Analysis-Report.pdf).**
- **The appendix will all relevant R codes can be found [here](./Cardiomyopathy-Survival-Analysis-Appendix.rmd).**

## Project Objectives

1. **Univariate Analysis**  
   Evaluate each predictor individually to determine which variables show a significant association with patient survival.

2. **Survival Analysis**  
   Assess whether predictors identified as significant in univariate analyses remain associated with survival when included together in a multivariable Cox model. Compare this reduced model to a full model containing all predictors.

3. **Model Comparison**  
   Determine which model provides a better explanation of patient survival using likelihood ratio tests, AIC, and proportional hazards diagnostics.
   

## Dataset

- 299 cardiomyopathy patients  
- 11 clinical, lifestyle, and body predictors  
- Follow-up time and mortality status  
- Variables include: age, gender, smoking status, creatinine, ejection fraction, sodium, blood pressure, BMI, and others.

## Methods

- Cox proportional hazards models 
- Logistic Regression
- Model comparison via:
  - Likelihood ratio tests  
  - Akaike Information Criterion (AIC)  
  - Concordance (c-index)

## Key Findings (Summary)

- Age, ejection percentage, and creatinine are significant independent predictors of survival in cardiomyopathy patients after adjusting for all other variables.

- Anaemia, CPK, and hypertension, not significant in univariate analyses, became significant in the full model, highlighting interactions with other predictors.

- Older age increases the instantaneous risk of death by ~4.5% per year, holding other variables constant.

- Higher ejection percentage reduces the instantaneous risk of death by ~4.4% per 1% increase, while higher creatinine increases risk by ~39% per unit.

- Sodium was retained for clinical relevance, and overall findings emphasize that age, cardiac function, and kidney function are primary factors influencing survival risk.


## Repository Structure


