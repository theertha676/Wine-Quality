# Wine-Quality
Machine learning project for 3skill

.

Wine Quality Prediction Using Machine Learning
Overview

This project demonstrates an end-to-end Machine Learning workflow to predict wine quality based on its chemical properties. The aim is to build, evaluate, and optimize multiple Machine Learning models and understand how real-world ML systems are developed from raw data to final predictions.

To make the problem more practical, the original quality scores are converted into a binary classification problem: Good Wine and Bad Wine.

📊 Dataset Description

Dataset Name: winequality.csv

Description: Each row represents a wine sample, and each column represents a chemical property such as acidity, alcohol, and sulphates.

Target Variable: quality

Classification Rule:

Quality ≥ 7 → Good Wine (1)

Quality < 7 → Bad Wine (0)

Project Objectives

Understand and analyze the dataset

Perform exploratory data analysis (EDA)

Prepare data for Machine Learning models

Train and compare multiple classification algorithms

Evaluate models using appropriate metrics

Improve performance using hyperparameter tuning

Technologies Used

Programming Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

🔄Project Workflow

Data loading and inspection

Data analysis and visualization

Feature engineering and target creation

Train-test split

Feature scaling

Model training

Model evaluation and comparison

Hyperparameter tuning using pipelines

Machine Learning Models

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Model Evaluation

Evaluation Metric: Accuracy

Multiple models are trained and compared

Random Forest and SVM achieved better performance

GridSearchCV is used to optimize model parameters

Key Learnings

Importance of data inspection and EDA

Role of feature scaling in ML models

Model comparison and selection

Use of pipelines to avoid data leakage

Practical understanding of end-to-end ML systems

Conclusion

This project provides hands-on experience in building a complete Machine Learning pipeline. It reflects real-world applications where data preprocessing, model evaluation, and optimization are essential for reliable predictions.

How to Run

Clone the repository

Install the required Python libraries

Place winequality.csv in the project directory

Run the Jupyter Notebook step by step
