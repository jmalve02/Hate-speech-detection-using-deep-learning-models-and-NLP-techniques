# Hate-speech-detection-using-deep-learning-models-and-NLP-techniques
NLP pipeline for classifying tweets using a Decision Tree Classifier. Includes text preprocessing, feature engineering with CountVectorizer, model training, evaluation, and interactive tweet classification. Great for beginners in NLP and ML.

Project: NLP Tweet Classification using Decision Tree Classifier
This project presents a simple yet effective pipeline for classifying tweets based on their text content, using natural language processing (NLP) techniques and a Decision Tree Classifier.

The goal is to showcase how classical machine learning models can be applied to textual data to build an interpretable classification model. The project is structured as a Jupyter Notebook and walks through each step of the process in detail.

Key Components:
1. Data Loading & Preparation
The dataset consists of tweets with corresponding class labels. The project maps the original labels to a target column and retains only relevant columns for further processing.

2. Text Preprocessing
To prepare the tweets for modeling, a series of NLP preprocessing steps are applied:

Tokenization: Splitting text into tokens

Stopword Removal: Eliminating common words with little semantic value

Stemming: Reducing words to their root forms

Custom Cleaning: Additional cleaning such as removing punctuation and converting text to lowercase

3. Feature Engineering
Tweets are transformed into a numerical format using CountVectorizer, which converts text into a matrix of token counts. Labels are encoded into numeric values to be used with the Decision Tree classifier.

4. Model Training & Evaluation
The processed data is split into training and test sets. A Decision Tree Classifier is trained on the training data and evaluated on the test data to assess its performance.

5. Interactive Prediction
An interactive function allows users to input new tweets, which are cleaned, vectorized, and classified in real-time.

Why Use This Project?
This project is ideal for beginners learning about:

Basic NLP techniques

Text classification workflows

Applying classical ML models to NLP tasks

Building interpretable models

It serves as a baseline for more complex models and can be easily extended with other classifiers (e.g., Random Forest, SVM) or modern deep learning techniques.


