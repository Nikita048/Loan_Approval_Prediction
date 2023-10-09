# Loan_Approval_Prediction

Overview

This project applies machine learning techniques to predict loan approval outcomes using a real-world loan application dataset from Kaggle. The goal is to benchmark diverse algorithms and identify the optimal model for implementing in real-world lending scenarios.

Data

The dataset contains 614 loan applications with various attributes like credit history, income, loan amount, dependents etc. The target variable is binary loan approval status (approved/not approved).

Methods

The project workflow includes:

Exploratory data analysis and visualization
Data preprocessing - missing value imputation, encoding, outlier removal etc.
Feature engineering using statistical tests like chi-square, correlation, ANOVA
Modelling using algorithms like logistic regression, SVM, decision trees, KNN, Naive Bayes, XGBoost etc.
Hyperparameter tuning via grid search and k-fold cross-validation
Comprehensive model evaluation using metrics like accuracy, precision, recall, F1-score etc.

Key Findings

The decision tree model achieved the best macro-averaged precision of 0.92, reflecting its ability to precisely predict each loan status.
Support Vector Machines reached 0.85 accuracy thanks to an appropriate linear kernel but lagged in per-class performance.
Logistic regression delivered 0.82 accuracy but linearity limitations resulted in poorer macro-precision of 0.77.
Heavily regularized single decision tree found the ideal balance between class-level precision and overall robust performance.

Conclusion

The study demonstrates the potential of machine learning in loan approval modelling while surfacing challenges and opportunities for improvement. Rigorous benchmarking, tuning and evaluation provided insights into model capabilities. Overall the research exemplifies best practices for trustworthy and ethical AI development.
