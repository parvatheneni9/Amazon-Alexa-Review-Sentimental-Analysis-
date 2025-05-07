Amazon-Alexa-Review-Sentimental-Analysis-
Built an NLP model using Logistic Regression to classify Amazon Alexa reviews as positive or negative. Applied TF-IDF vectorization, TextBlob sentiment scoring, and achieved 95% accuracy. Used Python, Scikit-learn, and Jupyter Notebook for implementation and evaluation.


 Project Goals

- Understand customer sentiment from product reviews
- Build a sentiment classification model
- Visualize insights from user feedback



Techniques Used

- Text Preprocessing (lowercasing, punctuation removal, stopwords)
- Tokenization and Lemmatization
- TF-IDF Vectorization
- Logistic Regression Model for Classification
- Sentiment Polarity Scoring using TextBlob
- Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report



 Dataset

- Source: Amazon Alexa product reviews dataset
- Fields:
  - `verified_reviews`: Text reviews from users
  - `feedback`: Binary sentiment label (1 = positive, 0 = negative)
  - `rating`, `variation`, and `date` (optional use in EDA)



 Model Performance

- Vectorizer: TF-IDF (Unigrams & Bigrams)
- Classifier: Logistic Regression
- Accuracy: 95% on the test set
- Evaluation:
- Precision, Recall, F1-Score
  - Confusion Matrix



Sample Output

- Top Positive Words
- Word Cloud of Positive vs. Negative Sentiments
- Polarity Distribution using TextBlob





