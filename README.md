# News-Article-Classification

# **Project Overview**
This project aims to classify news articles into one of five categories (sport, business, politics, entertainment, tech) using natural language processing (NLP) techniques and machine learning models. The project includes data preprocessing, feature extraction, model training and evaluation, and final prediction on a test dataset.

- There are 3 Excel files included:
  1. The testing data
  2. The training data
  3. The Label data, that will get overwritten

# **Table of Contents**
  - Project Overview
  - Dataset Description
  - Model Training and Evaluation
  - Results
    
# **Dataset Description**
- Training Data: 1064 news articles with labels.
  * CSV file with three columns: ArticleId, Text, and Category.
- Test Data: 736 news articles without labels.
  * CSV file with two columns: ArticleId, Text.

# **Model Training and Evaluation**
- Preprocessing
  - Lowercasing
  - Removing punctuation and digits
  - Tokenization
  - Stemming
  - N-gram generation
- Feature Extraction
  - CountVectorizer
  - TFIDF Vectorizer
- Models
  - Neural Network (PyTorch)
  - Logistic Regression
  - Multinomial Naive Bayes
- Cross-Validation
  - 5-fold cross-validation to evaluate model performance
    
# **Results**
The best performing model was a Neural Network with the following configuration:

- Two hidden layers with 128 neurons each
- Extracted features using CountVectorizer
- Achieved an average accuracy of 97.82% with cross-validation
