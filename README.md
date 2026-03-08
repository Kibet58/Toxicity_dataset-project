Toxicity Prediction Using Machine Learning
Overview

This project builds a machine learning model to classify chemical compounds as Toxic or Non-Toxic using molecular descriptor data. The workflow includes Exploratory Data Analysis (EDA), preprocessing, feature selection, class balancing using SMOTE, and training an ensemble model (Random Forest) with cross-validation.

Dataset

The dataset contains molecular descriptor features used to predict toxicity.

Target column: Class

Classes:

0 → Non-Toxic

1 → Toxic

Workflow

Data loading and inspection

Exploratory Data Analysis (EDA)

Handling missing values

Feature/target separation

Train-test split

Class balancing using SMOTE

Feature selection

Model training using Random Forest

Cross-validation

Model evaluation

Evaluation Metrics

Precision

Recall

F1-Score

Accuracy

Confusion Matrix

Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

Author

Kibet
