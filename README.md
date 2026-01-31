🚀 Nova Gen – Machine Learning Model Comparison

This project focuses on training, evaluating, and comparing multiple Machine Learning classification models on a given dataset.
The goal is to analyze model performance using standard evaluation metrics and identify the most effective model for the problem.

📁 Project Structure
Nova-Gen/
│
├── nova_gen.ipynb   # Main Jupyter Notebook
├── novagen_dataset.csv  # Dataset (if included)
└── README.md

📌 Project Overview

The Jupyter Notebook performs the complete machine learning workflow, including data preprocessing, model training, and performance evaluation.
Multiple classification algorithms are implemented and compared based on their evaluation metrics.

🤖 Models Used

The following Machine Learning models are trained and tested:
Logistic Regression
Decision Tree Classifier (tested with different max_depth values)
Random Forest Classifier
Support Vector Machine (SVM)
Gradient Boosting Classifier

🔄 Workflow
The notebook follows these steps:
Load the dataset
Convert dataset values to integer format (if applicable)
Check for missing values and duplicate records
Split the dataset into training and testing sets
Train multiple classification models
Evaluate each model’s performance

📊 Evaluation Metrics
Model performance is evaluated using the following metrics:
Accuracy
Precision
Recall
F1-score
A detailed classification report is generated for each model to provide deeper insight into performance.

🛠️ Technologies & Libraries Used
Python
Pandas
NumPy
Scikit-learn
Jupyter Notebook

🎯 Objective
The primary objective of this project is to:
Compare different classification algorithms
Understand their strengths and weaknesses
Identify the best-performing model based on evaluation metrics

📌 How to Run
Clone the repository
git clone https://github.com/your-username/Nova-Gen.git

Open the notebook
jupyter notebook nova_gen.ipynb

Run all cells sequentially

📈 Results

Each model’s performance is printed in the notebook using accuracy scores and classification reports, enabling easy comparison and analysis.

📜 License

This project is for educational and learning purposes.
