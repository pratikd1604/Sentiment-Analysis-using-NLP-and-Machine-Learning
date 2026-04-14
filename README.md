# Sentiment-Analysis-using-NLP-and-Machine-Learning
Machine Learning-based sentiment analysis on 75K+ tweets using NLP techniques and Random Forest, achieving 97% accuracy.

**Overview :**
This project focuses on building a machine learning model to classify textual data (tweets) into Positive, Negative, and Neutral sentiments. It demonstrates how unstructured text data can be transformed into meaningful insights using NLP techniques.

**Dataset :**
https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

**Key Points :**
Processed and analyzed 75,000+ tweets with 4 key features
Converted raw text into numerical format using CountVectorizer
Applied Label Encoding for target variable transformation
Built a Random Forest Classifier for sentiment prediction
Achieved 97% accuracy with strong classification performance

**Tools and Libraries :**
Python
Pandas, NumPy
Scikit-learn
NLTK

**Workflow :**
Data Cleaning (handling missing values and duplicates)
Text Preprocessing 
Label Encoding of target variable
Train-Test Split (80–20)
Model Training using Random Forest
Performance Evaluation (Accuracy, Precision, Recall, F1-score)

**Results :**
The model successfully classifies tweet sentiments with 97% accuracy, demonstrating strong capability in handling large-scale textual data.

**Limitations :**
1. Uses Bag-of-Words approach (does not capture context or word order)
2. Limited handling of sarcasm and complex language patterns

