Task 3 – Sentiment Classification (K-Nearest Neighbors)

Goal: Predict simplified sentiment (Positive / Neutral / Negative) from social-media post metadata.

Dataset
sentimentdataset.csv

Workflow
1. Cleaned and simplified 279 raw sentiment labels into 3 main classes.  
2. Balanced the dataset by random oversampling.  
3. Selected numeric features: `Likes`, `Retweets`, `Hour`, `Day`, `Month`.  
4. Scaled features with StandardScaler.  
5. Trained a **KNeighborsClassifier (k = 5).  
6. Evaluated model accuracy, precision, recall, F1 and confusion matrix.  
7. Visualized:  
   - Bar chart → predicted sentiment distribution.  
   - Line plot → accuracy vs K to choose optimal k.

Key Learning
- Handling class imbalance and data scaling in KNN.  
- Interpreting model performance with visual tools.

▶️ How to Run
bash
pip install -r ../../requirements.txt
jupyter notebook knn_sentiment.ipynb
