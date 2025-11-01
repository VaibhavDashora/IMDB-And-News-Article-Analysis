🎯 Project 1: IMDb Sentiment Analysis
Objective
Build a binary classification model to predict sentiment (positive/negative) from IMDb movie reviews.

Workflow
Data Cleaning: Lowercasing, removing punctuation, stopwords, and lemmatization.

Feature Engineering: TF-IDF vectorization (max 5000 features).

Models Used:

Logistic Regression ✅ Best performer (Accuracy: 88.6%)

Naive Bayes

Support Vector Machine

Random Forest

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Highlights
Positive reviews tend to be longer and more descriptive.

Emotion-rich adjectives drive sentiment polarity.

TF-IDF helps isolate impactful words for classification.



🗞️ Project 2: News Article Classification
Objective
Automatically classify news articles into categories like politics, sports, wellness, etc.

Workflow
Data Cleaning: Applied to short descriptions and headlines.

Feature Extraction:

Bag-of-Words (unigrams)

TF-IDF (unigrams + bigrams)

Models Used:

Logistic Regression

Naive Bayes

Support Vector Machine ✅ Best performer (Accuracy: 64.5%)

Evaluation Metrics: Accuracy, Macro F1-score, Cross-validation, Confusion Matrix

Highlights
TF-IDF reveals top category-specific keywords.

Balanced dataset with 10 categories.

Combined headline + description improves context.
