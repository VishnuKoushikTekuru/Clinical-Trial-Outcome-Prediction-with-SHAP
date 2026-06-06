# Clinical Trial Outcome Prediction with SHAP Explainability

Predicting malignant vs benign clinical outcomes using machine learning,
with SHAP values for transparent model explainability.

## What this does
- Compares Logistic Regression, Random Forest, and XGBoost classifiers
- Evaluates using precision, recall, F1, and AUC-ROC
- Uses SHAP to explain which features drive each prediction
- Produces visualisations suitable for both technical and clinical audiences

## Why explainability matters
In health and care settings, knowing *why* a model makes a prediction
is as important as the prediction itself. SHAP values make the model
transparent and auditable — essential for responsible AI in healthcare.

## Key finding
XGBoost achieved the highest AUC-ROC. The SHAP summary plot shows
[describe your actual finding here once you run it].

## Stack
Python, Scikit-learn, XGBoost, SHAP, Pandas, Matplotlib, Seaborn

## Dataset
Breast Cancer Wisconsin (Diagnostic) — UCI ML Repository via Sklearn
