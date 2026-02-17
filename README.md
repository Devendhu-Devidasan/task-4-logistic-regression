# task-4-logistic-regression
AI &ml; ML Internship - Task 4: Classification using Logistic Regression
📌 Objective

The objective of this project is to build a binary classification model using Logistic Regression to predict whether a tumor is malignant or benign.

📊 Dataset Used

Breast Cancer Wisconsin Dataset

Total Samples: 569

Features: 30 numerical features

Target:

0 → Malignant

1 → Benign

🛠 Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Scikit-learn

🚀 Steps Performed

Imported required libraries

Loaded the dataset

Split data into training and testing sets

Standardized the features using StandardScaler

Trained a Logistic Regression model

Evaluated the model using:

Confusion Matrix

Precision

Recall

ROC-AUC Score

ROC Curve

📈 Model Evaluation
🔹 Confusion Matrix

Shows True Positives, True Negatives, False Positives, and False Negatives.

🔹 Precision

Indicates how many predicted positives were actually correct.

🔹 Recall

Indicates how many actual positives were correctly identified.

🔹 ROC-AUC Score

Measures the overall performance of the classifier across all thresholds.

📉 Sigmoid Function

Logistic Regression uses the sigmoid function:

σ(z) = 1 / (1 + e⁻ᶻ)

It converts predictions into probability values between 0 and 1.

📌 Results

The model achieved high accuracy and strong ROC-AUC performance, showing that Logistic Regression is effective for binary classification problems.

📂 Repository Structure
Task-4-Logistic-Regression/
│
├── logistic_regression.ipynb
├── README.md
└── screenshots/
🎯 Conclusion

Logistic Regression is a powerful and simple algorithm for binary classification tasks.
This project demonstrates how to train, evaluate, and interpret a classification model using real-world data.
