# Cardiomyopathy-Survival-Analysis


## Cardiomyopathy Survival Analysis

This project examines clinical, lifestyle, and body characteristics associated with survival among patients diagnosed with cardiomyopathy. The analysis uses Cox proportional hazards models to identify predictors of time-to-death and compare model performance.

## Project Objectives

1. **Univariate Analysis**  
   Evaluate each predictor individually to determine which variables show a significant association with patient survival.

2. **Multivariable Modeling**  
   Assess whether predictors identified as significant in univariate analyses remain associated with survival when included together in a multivariable Cox model. Compare this reduced model to a full model containing all predictors.

3. **Model Comparison**  
   Determine which model provides a better explanation of patient survival using likelihood ratio tests, AIC, and proportional hazards diagnostics.

## Dataset

- 299 cardiomyopathy patients  
- 11 clinical, lifestyle, and body predictors  
- Follow-up time and mortality status  
- Variables include: age, gender, smoking status, creatinine, ejection fraction, sodium, blood pressure, BMI, and others.

## Methods

- Cox proportional hazards models (`coxph` in R)
- Univariate screening of all predictors
- Multivariable model building (reduced vs. full)
- Schoenfeld residuals for proportional hazards diagnostics
- Model comparison via:
  - Likelihood ratio tests  
  - Akaike Information Criterion (AIC)  
  - Concordance (c-index)

## Key Findings (Summary)

- Several predictors show significant univariate associations with survival (e.g., age, ejection fraction, creatinine, sodium).
- Some predictors remain significant in the multivariable model, indicating independent effects.
- The reduced model performs as well as or better than the full model, suggesting that not all variables contribute meaningful predictive value.

## Tools Used

- **R** (survival, survminer, tidyverse)
- R Markdown / Quarto for reporting
- GitHub for version control

## Repository Structure


