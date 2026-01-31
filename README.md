Nova Gen - Machine Learning Model Comparison
This project contains a Jupyter Notebook that trains and compares multiple Machine Learning classification models on a dataset, evaluates their performance, and prints detailed results.

Project Files
nova_gen.ipynb — Main notebook containing data preprocessing, training, and evaluation
Models Used
The notebook trains and tests the following models:

Logistic Regression
Decision Tree (tested with different max depths)
Random Forest
Support Vector Machine (SVM)
Gradient Boosting Classifier
Workflow
The notebook follows these steps:

Load the dataset
Convert dataset values to integer format (if applicable)
Check for missing values and duplicates
Split data into training and testing sets
Train multiple models
Evaluate models using:
Accuracy Score
Classification Report
Evaluation Metrics
Model performance is evaluated using:

Accuracy
Precision
Recall
F1-score
