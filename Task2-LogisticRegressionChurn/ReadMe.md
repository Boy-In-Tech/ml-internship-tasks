Task 2 – Customer Churn Prediction (Logistic Regression)

Goal: Predict whether a telecom customer will churn.

Datasets
churn-bigml-80.csv` → training set  
churn-bigml-20.csv` → test set

Workflow
1. Loaded train/test data with pandas.  
2. Encoded categorical and numeric features using ColumnTransformer  
   – `OneHotEncoder` for categoricals  
   – `StandardScaler` for numerics  
3. Trained a LogisticRegression model (`class_weight='balanced').  
4. Evaluated using Accuracy, Precision, Recall, F1 and ROC AUC.  
5. Visualized the ROC curve and inspected feature coefficients to odds ratios.  
6. Saved model + preprocessor via joblib`.

Key Learning
- Logistic regression fundamentals and interpreting coefficients.  
- Balancing imbalanced data and understanding evaluation metrics.

How to Run
bash
pip install -r ../../requirements.txt
jupyter notebook churn_model.ipynb
