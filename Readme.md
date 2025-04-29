
# Credit Risk Prediction for Loan Applicants

## Overview
This project develops a machine learning model to predict credit risk for loan applicants, helping banks make better lending decisions. Using the German Credit Dataset, the model analyzes various applicant attributes to determine creditworthiness with high accuracy.

## Problem Statement
Banks face challenges in identifying reliable borrowers. Manual credit checks are often:
- Time-consuming
- Potentially biased
- Inconsistent

Our prediction model addresses these issues by providing fast, objective, and accurate risk assessments.

## Dataset
The German Credit Dataset with 1000 entries containing attributes:
- Age (numeric)
- Sex (male, female)
- Job (0-3 skill levels)
- Housing (own, rent, free)
- Saving accounts (little, moderate, quite rich, rich)
- Checking account (numeric)
- Credit amount (numeric)
- Duration (in months)
- Purpose (car, furniture/equipment, radio/TV, etc.)

## Methodology
- **Algorithm**: XGBoost (Extreme Gradient Boosting)
- **Feature Scaling**: StandardScaler
- **Validation**: Train-test split with stratification + 5-fold cross-validation

## Results
- **Precision**: 92.53%
- **Accuracy**: 95.39%
- **Recall**: 94%
- **F1-score**: 93.30%

## Key Findings
- Most influential features for prediction are Credit Amount and Duration
- The model generalizes well across different subsets of data

## Conclusion
The project demonstrates that machine learning can effectively predict loan applicant credit risk with high accuracy, helping financial institutions make data-driven decisions that reduce default risk while improving efficiency and fairness.

## Future Recommendations
- Enhance data collection with wider financial information
- Regularly update applicant profiles
- Combine traditional scoring with behavioral data analysis

## References

- [View Project PPT](https://drive.google.com/file/d/1_V6V9RrHQmYrvkUvE1_X1r-Srh2KXFEb/view?usp=sharing)
---
*Project by Saahibah Baig (CT20234251692)*
