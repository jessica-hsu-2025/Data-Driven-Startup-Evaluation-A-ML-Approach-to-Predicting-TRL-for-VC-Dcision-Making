## Overview
This project explores different machine learning models and optimization techniques to enhance predictive performance. The models evaluated include Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. The project implements train-validation-test splits, cross-validation, and GridSearchCV for hyperparameter tuning.

## Dataset
- The dataset consists of 150 rows with class imbalance, which posed challenges in prediction accuracy.
- Features are a mix of numerical and categorical variables, requiring preprocessing such as scaling.

## Models Implemented
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting

## Optimization Approaches: can be seen in Optimization 1, 2, and 3
- Train-Validation-Test Split: Initial evaluation of models on split data.
- Cross-Validation: Improved performance by reducing overfitting and ensuring robust model evaluation.
- GridSearchCV: Tuned hyperparameters for all models, leading to noticeable performance improvements.

## Key Findings
- Random Forest demonstrated the most improvement, increasing accuracy by 7% after hyperparameter tuning.
- Gradient Boosting saw a 10% increase in precision for minority class predictions after fine-tuning.
- Logistic Regression and Decision Tree models had moderate improvements but still struggled with class imbalance.

## Possible Future Enhancements
- Implement Bayesian Optimization or Random Search for more efficient hyperparameter tuning.
- Explore feature engineering and dimensionality reduction (PCA) to improve model interpretability and performance.
- Address class imbalance with resampling techniques such as SMOTE or class-weight adjustments.
- Consider ensemble learning (stacking or boosting) to combine model strengths.

## Contributors
- Jessica Hsu (@jessica-hsu-2025)


