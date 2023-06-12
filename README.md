# InboxDefender
NLP-based approach to combat spam emails, leveraging data cleaning, vectorizing, feature engineering, and ML classifiers for accurate detection. Tackles challenge of distinguishing ham from spam in email communication.
The project begins with a comprehensive data cleaning process that removes noise, handles missing values, and standardizes text data. Next, a range of powerful vectorization techniques, such as bag-of-words, TF-IDF, and word embeddings, are applied to transform the textual content of emails into numerical representations that can be effectively processed by machine learning algorithms.
To enhance the predictive capabilities, In employs advanced feature engineering methods to extract meaningful patterns and characteristics from the email data. These features encompass both syntactic and semantic aspects, including textual patterns, and linguistic attributes.
The feature-rich dataset is then fed into a diverse set of machine learning classifiers, Random Forests, and Gradient-Boosting. These classifiers are trained on labeled data consisting of known spam and ham emails, allowing them to learn the underlying patterns and make accurate predictions on unseen emails.
The project also incorporates a comprehensive evaluation framework to assess the performance of the classifiers, using metrics like precision, recall, F1 score, and area under the receiver operating characteristic curve (AUC-ROC). This evaluation process helps fine-tune the models, ensuring optimal performance in distinguishing spam from legitimate emails.

Project Timeline:
1. Data Cleaning - Rewmoved punctuation, stopwords, tokenization etcetera.
2. Lemmatizing the tokens
3. Vectorization - Count Vectorization, N-grams vectorization, TFIDF Vectorization.
4. Featuew Engineering
5. Hyperparameter Tuning using K- fold Validation
6. Training Machine learning models - RandomForestClassifier, GradientBoosting.
