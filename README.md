# Using Explainable AI Method SHAP to Improve Trust in Automated Credit Scoring for Small Business Loans
## 1. Overview: This bachelor thesis focuses on improving the transparency and trustworthiness of automated credit scoring systems for small and medium-sized enterprises (SMEs). The project applies Explainable Artificial Intelligence (XAI) techniques, specifically SHAP (SHapley Additive exPlanations), to interpret machine learning models and enhance decision-making in financial systems.
## 2. Problem Statement: Traditional credit scoring models rely heavily on formal financial data and often fail to accurately assess SMEs due to incomplete records and irregular income. While AI-based models improve prediction accuracy, they operate as “black boxes,” raising concerns about trust, fairness, and accountability.
## 3. Objective: The main objective of this project is to investigate how SHAP can improve trust in automated credit scoring systems across four dimensions:Technical,Ethical,Legal and Social
## 4. Dataset: The project uses multiple datasets containing:
                 1. Applicant personal information (application_train)
                 2. Credit bureau data(bureau)
                 3. Historical repayment behavior(bureau_balance)
## 5. Dataset Access :The dataset is stored on a private Google Drive and is not publicly accessible.
                    To run this project:
                   1. Download the dataset from: (https://www.kaggle.com/c/home-credit-default-risk )
                   2. Upload it to your own Google Drive
                   3. Update the file path in the notebook accordingly
## 6.Methodology: The project follows the CRISP-DM methodology:
                   1.Business Understanding
                   2.Data Understanding
                   3.Data Preparation
                   4.Modeling
                   5.Evaluation
                   6.Deployment
## Data Processing:
                  Data cleaning and handling missing values
                  Feature engineering and aggregation
                  Merging multiple datasets
## Models Used:
                  XGBoost
                  LightGBM
                  CatBoost
## Evaluation Metrics: Models were evaluated using

                  ROC-AUC (discrimination ability)
                  Brier Score (probability accuracy)
                  Expected Calibration Error (ECE)
                  Kendall Tau (SHAP stability)
                  Explainability (SHAP)

## SHAP was applied to:

                  Explain individual predictions (local interpretability)
                  Identify important features globally
                  Detect potential bias and fairness issues
                  Generate interpretable visualizations (summary plots, force plots)
## Results:
                  CatBoost achieved the best balance between performance and reliability
                  SHAP provided clear insights into model behavior
                  Financial features were the strongest predictors
                  Explainability improved transparency and supported fairness analysis
## How to Run:
                  1.Open the notebook in Google Colab
                  2.Upload the dataset to your Google Drive
                  3.Update file paths in the notebook
                  4.Run all cells
## Requirements:
                  pandas
                  numpy
                  scikit-learn
                  xgboost
                  lightgbm
                  catboost
                  shap
## Author:

## Laila Sherif Aly Youssef Helal
## German University in Cairo
## Supervisor:
## Dr. Hany Ismail
