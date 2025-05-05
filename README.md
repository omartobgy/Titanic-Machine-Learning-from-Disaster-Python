# Titanic-Machine-Learning-from-Disaster-Python

This project is based on the [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition, which challenges participants to predict passenger survival based on historical data.

## 🔍 Overview

Using Kaggle’s official Titanic datasets, this project:
- Cleans and processes training/test data
- Handles missing values
- Encodes categorical features
- Trains and compares multiple classifiers
- Outputs a submission-ready prediction file

## 🛠 Tools & Libraries
- Python
- pandas
- scikit-learn
- Jupyter Notebook

## 🧠 Key Features
- Used Kaggle's `train.csv`, `test.csv`, and `gender_submission.csv`
- Imputed missing values in Age, Fare, and Embarked
- Encoded class, sex, and port variables
- Compared Logistic Regression, Decision Tree, and Random Forest
- Generated predictions for submission to Kaggle format

## 📈 Sample Results
- Random Forest achieved 78% accuracy on validation data
- Logistic Regression and Decision Tree provided useful baseline comparisons
- Precision for Decision Tree improved by 12% after tuning

## 📁 Files
- `train.csv`: Kaggle training data
- `test.csv`: Kaggle test data (unlabeled)
- `gender_submission.csv`: Sample submission format from Kaggle
- `Titanic - Machine Learning from Disaster.ipynb`: Main notebook with full pipeline

## ✅ How to Run
1. Clone the repository
2. Install required packages:
   ```bash
   pip install pandas scikit-learn
