1. Essential libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, and `imbalanced-learn` are imported for data analysis, modeling, and visualization.

2. The column `Attrition` is selected as the target (label) for prediction (Yes = employee left, No = stayed).

3. Label Encoding is applied to all object-type columns to simplify them into numeric values, suitable for ML algorithms.

4. The balanced dataset (after SMOTE) is split into training and test sets to evaluate model generalization.

5. A `random_state=42` is used to ensure reproducibility of results when splitting data or applying SMOTE.

6. Class imbalance in `Attrition` is handled deliberately to prevent bias toward the majority class (employees who stayed).

7. By testing 3 models (Logistic Regression, Random Forest, XGBoost), you compare different algorithm strengths.

8. Special emphasis is placed on recall, since predicting employees likely to leave (true positives) is more important.

9. EDA plots help HR teams visually understand attrition trends across job roles and departments.

10. The end goal is actionable insight — helping HR teams proactively address employee attrition using data-driven strategies.

