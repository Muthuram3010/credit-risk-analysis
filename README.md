# credit-risk-analysis
This project focuses on building an explainable AI model for credit risk analysis using machine learning and SHAP (SHapley Additive exPlanations). The model predicts the likelihood of credit default and provides clear, interpretable insights into the factors influencing each prediction.

This code demonstrates how to train a machine learning model for credit risk assessment using Gradient Boosting and provides an explanation of individual predictions using SHAP (SHapley Additive exPlanations) for interpretability.

Model: A GradientBoostingClassifier is trained to predict a binary target (malignant or benign tumor in the dataset).
Interpretability: The SHAP library is used to explain the model's predictions by calculating feature importance and providing natural language explanations.
