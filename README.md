This project aims to classify news articles as FAKE or REAL using natural language processing (NLP) and machine learning. It utilizes the Passive Aggressive Classifier, which is particularly efficient for large-scale classification tasks such as online learning.

📌 Key Steps:
Data Loading:

The news.csv file is loaded, which contains text articles and their corresponding labels (FAKE or REAL).

Text Preprocessing:

A TF-IDF Vectorizer is used to convert text data into numerical format, filtering out common stop words and limiting features by document frequency.

Model Training:

The data is split into training and testing sets (60% training, 40% testing).

A Passive Aggressive Classifier is trained on the TF-IDF-transformed training data.

Evaluation:

The model's performance is evaluated using accuracy score, confusion matrix, and a classification report (precision, recall, F1-score).

A seaborn heatmap is used to visualize the confusion matrix for better understanding of correct vs. incorrect classifications.

✅ Outcome:
The classifier predicts whether a news article is fake or real based on its text.

This model is effective for identifying misinformation in online news content.

