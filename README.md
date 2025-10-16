This repository contains my completed tasks during a Machine Learning Internship program. 
Each folder represents a major task focused on core ML principles — from data preprocessing to supervised learning and model evaluation

Task Overview:
Task 1 — Data Preprocessing for Machine Learning

Goal: Prepare raw data for model training.

Key Steps:

    Handled missing values (using mean/median).
    Encoded categorical variables.
    Normalised numerical features.
    Split data into training and test sets.

Dataset: House Price Prediction Data.
Libraries Used: pandas, scikit-learn, numpy
Result: A clean, fully preprocessed dataset ready for ML modelling.


Task 2 — Logistic Regression for Binary Classification

Goal: Predict whether a customer will churn using Logistic Regression.

Key Steps:

    Preprocessed categorical and numerical features using ColumnTransformer.
    Trained a logistic regression model with Scikit-Learn.
    Interpreted coefficients and odds ratios.
    
Evaluated model using:

    Accuracy
    Precision & Recall
    F1-Score
    ROC-AUC curve

Dataset: Telecom Churn Dataset (churn-bigml-80.csv, churn-bigml-20.csv)
Libraries Used: pandas, scikit-learn, matplotlib, numpy, joblib
Result: A balanced, well-performing model capable of identifying potential churners.



Task 3 — Sentiment Analysis using KNN

Goal: Classify user posts as Positive, Neutral, or Negative using the K-Nearest Neighbours algorithm.

Key Steps:

    Cleaned and simplified text sentiment labels.
    Encoded categorical data numerically.
    Split the dataset into training and test sets.
    Trained and evaluated the KNN classifier.

Dataset: Social Media Sentiment Dataset.
Libraries Used: pandas, scikit-learn, numpy
Result: Achieved over 75% accuracy with simplified sentiment grouping.



Setup Instructions

1. Clone the repository:

        git clone https://github.com/Boy-In-Tech/ml-internship-tasks.git
        cd ml-internship-tasks


2. Install dependencies:

       pip install -r requirements.txt
(You can generate this later with pip freeze > requirements.txt.)

3. Open Jupyter Notebooks:

       jupyter notebook

Then open any of the task folders to explore the code.

Folder Structure
ml-internship-tasks/
│
├── Task1_Data_Processing/
│   └── HousePrice_Preprocessing.ipynb
│
├── Task2-LogisticRegressionChurn/
│   ├── ChurnPrediction.ipynb
│   ├── churn-bigml-80.csv
│   └── churn-bigml-20.csv
│
├── Task3_Sentiment_Knn/
│   ├── SimplifiedSentiment.ipynb
│   └── SentimentDataset.csv
│
└── .gitignore

Tools & Environment
Python 3.9+
Jupyter Notebook
scikit-learn
pandas
numpy
matplotlib



Highlights

Gained hands-on experience with real datasets.
Practised feature scaling, encoding, and model interpretation.
Improved understanding of supervised learning workflows.



Author

Oluwatimileyin Oluwasegun Zion
Aspiring AI Engineer | Machine Learning Enthusiast | Passionate about integrating AI and Machine Learning with software solutions.
