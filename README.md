# ASD Prediction Using AQ-10 Screening and Demographic Data

This project investigates the use of machine learning and statistical models to predict Autism Spectrum Disorder (ASD) based on AQ-10 screening questionnaire results and demographic features.

**Note:** Due to academic submission policies, the full report and source code will be uploaded after the term ends (July 2025).

## Project Overview

- **Topic:** Early prediction of ASD using digital screening tools
- **Techniques Used:**  
  - Logistic Regression (with LASSO)
  - Random Forest, XGBoost
  - Support Vector Machine
  - Artificial Neural Network  
- **Imputation & Preprocessing:**  
  - PMM, polytomous logistic regression (MICE package)
  - Recalculation of AQ-10 scores
  - Feature engineering for modeling
- **Evaluation Metrics:**  
  - AUC, accuracy, precision, sensitivity, specificity, Kappa score

## Key Highlights

- XGBoost achieved the highest overall performance (AUC = 0.913)
- LASSO regression offered the most interpretable results
- AQ-10 score and family history were the strongest predictors

## Tools & Libraries

- **Language:** R
- **Key Libraries:** `caret`, `glmnet`, `xgboost`, `mice`, `nnet`
- **Environment:** RStudio

