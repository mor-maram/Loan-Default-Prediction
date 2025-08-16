# Loan-Default-Prediction
This project predicts whether a borrower will default on a loan using the K-Nearest Neighbors (KNN) algorithm. It includes data preprocessing, model training, evaluation, and export for future use.

Dataset

The dataset Loan_default.csv contains loan applicant information with the following features:

Numerical features: Age, Income, LoanAmount, CreditScore, MonthsEmployed, NumCreditLines, InterestRate, LoanTerm, DTIRatio

Categorical features: Education, EmploymentType, MaritalStatus, HasMortgage, HasDependents, LoanPurpose, HasCoSigner

Target: Default (0 = No Default, 1 = Default)

Project Overview

Data Upload and Loading: The dataset is uploaded and loaded for analysis.

Data Preprocessing: Numerical features are scaled, and categorical features are one-hot encoded.

Data Splitting: The data is split into training and testing sets.

Model Training: K-Nearest Neighbors (KNN) is trained to predict loan default. Logistic Regression is also implemented in a pipeline for comparison.

Model Evaluation: Model performance is evaluated using accuracy, confusion matrix, and classification report.

Model Export: The trained model is saved for future predictions.

Model Performance

KNN Accuracy: ~88%

Confusion Matrix and Classification Report indicate the model performs well on non-default cases but has lower recall for default cases.

Conclusion

The project demonstrates a practical approach to predicting loan defaults using machine learning.

Preprocessing and pipelines ensure consistent and reproducible results for new data.

Both KNN and Logistic Regression provide insights into classification performance for loan default prediction.
