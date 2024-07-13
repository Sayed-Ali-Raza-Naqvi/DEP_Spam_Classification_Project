# Spam Classification Project
This project demonstrates the use of Naive Bayes classifiers (MultinomialNB, GaussianNB, BernoulliNB) to detect spam messages from a dataset. The project includes data preprocessing, feature extraction using TF-IDF, and model evaluation.

## Dataset
The dataset used in this project is `spam_ham_dataset.csv`. It contains labeled text messages, which are categorized as spam or ham.

## Dependencies
- pandas
- numpy
- string
- nltk
- scikit-learn

## Data Preprocessing
- Loading Data: The dataset is loaded into a pandas DataFrame.
- Cleaning Data: Remove unnecessary columns and clean text data by:
  - Removing line breaks
  - Converting text to lowercase
  - Removing punctuation
  - Removing stopwords
  - Applying stemming

## Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert the text data into numerical features.

## Model Training
Three different Naive Bayes classifiers are used:
- MultinomialNB
- GaussianNB
- BernoulliNB

## Evaluation
The performance of each classifier is evaluated using accuracy score and confusion matrix.

## Acknowledgments
- Kaggle
- NeuralNine (YouTube Channel)
