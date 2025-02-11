# LendingClub Loan Default Prediction

## Project Title: Credit Risk Modeling and Strategy Optimization for Loan Default Prediction

### Dataset Overview 
The objective of this project is to predict loan defaults by analyzing borrower profiles, financial indicators, and loan details. The dataset, sourced from LendingClub, contains up to 2 million loan records (depending on the version) and includes around 50+ features, which vary based on the specific version of the dataset used.

### Purpose of the Project
1. Predict loan defaults and optimize credit risk models for better lending decisions.
2. Develop strategies for minimizing defaults and improving loan approvals.

## Model Development and Evaluation

1. Performed exploratory data analysis (EDA) on loan status, borrower profiles, and financial indicators, identifying key risk factors driving defaults.
2. Segmented borrowers by risk levels, analyzing loan amount, interest rates, debt-to-income ratio, and employment tenure to refine lending strategies.
3. Implemented advanced data preprocessing, including handling missing data (reducing by 30%) and applying under-sampling techniques to address class imbalance.
4. Engineered predictive features, leveraging correlation analysis, feature scaling, and transformations, optimizing model accuracy and robustness.
5. Developed a credit risk model using Logistic Regression and XGBoost, increasing AUC-ROC from 0.72 to 0.85 and improving recall for high-risk borrowers by 36%.
6. Optimized probability thresholds via model calibration, reducing false negatives and financial losses by $419M, improving recall for loan defaulters.
7. Developed a risk-based credit strategy, implementing acceptance rate thresholds and dynamic pricing models, optimizing loan approvals and minimizing defaults.
8. Designed interactive dashboards visualizing risk trends, ROC curves, and calibration plots, enabling data-driven lending decisions and reducing bad loan approvals.
