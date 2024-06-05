# Credit Risk Assessment with Machine Learning
This project investigates the use of machine learning to predict customer defaults on credit card loans. Financial institutions face significant challenges in managing credit risk, and machine learning offers a powerful approach to assess customer creditworthiness and inform lending decisions.

# Project Goal

Develop and evaluate machine learning models to predict credit card loan defaults, aiding banks in optimizing risk management strategies and improving lending decisions.

# Methodology

## Data Acquisition

A dataset containing credit card customer information was obtained (source remains confidential).

## Data Preprocessing

Missing values were imputed using appropriate techniques based on data type (e.g., mode imputation for categorical data).
Outliers were addressed using winsorization to mitigate their impact on model performance.
Feature engineering involved creating new features (e.g., total income) to enhance model generalizability.
Feature selection techniques (e.g., tree-based methods) were employed to identify and retain the most relevant features for model training.
Class imbalance was addressed using resampling techniques (e.g., SMOTE) to ensure a balanced representation of both defaulting and non-defaulting customers.

## Model Development

Various machine learning algorithms were explored, including Random Forest and XG Boost.
Hyperparameter tuning was performed using GridSearchCV to optimize model performance.

# Results

The developed models achieved moderate performance in predicting loan defaults. Metrics like accuracy, precision, recall, F1-score, and ROC AUC were used for evaluation. While both models exhibited underfitting tendencies, XG Boost demonstrated slightly better results compared to Random Forest.

# Limitations

Underfitting of models suggests potential limitations in capturing the full complexity of the data.
The models could benefit from a larger and more comprehensive dataset.

# Conclusion

This project demonstrates the potential of machine learning for credit risk assessment in the financial sector. While the current models require further refinement, they provide a solid foundation for future development.

# Future Work

Acquire additional data sources to enrich model training.
Explore alternative data sources (e.g., social media sentiment, purchase history) for a more holistic view of borrower financial health.
Investigate the use of more advanced machine learning algorithms (e.g., neural networks).
Implement dynamic models that can adapt to evolving market conditions.

This project serves as a starting point for developing robust machine learning models to support credit risk assessment and empower financial institutions with informed lending decisions.
