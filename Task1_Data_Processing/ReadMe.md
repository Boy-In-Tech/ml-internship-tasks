# Task 1 – Data Preprocessing for Machine Learning

Goal: Clean and prepare a raw dataset so it is ready for modeling.

📄 Dataset
housePredictionDataSet.csv` — Boston Housing–style numeric data with 14 features (CRIM, ZN, INDUS, …, MEDV).

Steps Performed
1. Loaded the dataset with **pandas**.
2. Assigned proper column names.
3. Checked for and handled missing values.
4. Scaled numerical features using StandardScaler.
5. Split data into training and testing subsets.

Key Learning
- Importance of consistent preprocessing for ML pipelines.  
- How feature scaling improves model convergence and interpretability.

### ▶️ How to Run
bash
pip install -r ../../requirements.txt
jupyter notebook preprocessing.ipynb
