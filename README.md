# Sentiment_analysis_Micro_IT_Project-
This repository contains a project-- the task that i accomplished in my internship at MICRO IT.

Task: Sentiment analysis using machine learning (Naive Bayes);
This is a simple **Sentiment Analysis** project built using Python, scikit-learn, and a Naive Bayes classifier. The project classifies text into sentiment categories (e.g., positive, negative, neutral) based on a dataset of labeled text samples.

Used an open source dataset of social media reviews for sentiment analysis, on the basis of this dataset the model predicts whether the input-text is a postive, neutral or negative review. 

---

## Features

- Preprocesses and cleans textual data
- Uses `CountVectorizer` for converting text to numeric features
- Trains a `MultinomialNB` (Naive Bayes) classifier
- Accepts custom text input and predicts sentiment in real-time
- Easy to extend with better vectorizers or models (like TF-IDF or BERT)

---

## Project Structure & Description
sentiment-analysis/
│
├── sentiment_analysis.ipynb # Main Python script for loading data, training the model, and predicting sentiment
├── sentiment_analysis.csv # Dataset containing text samples and their sentiment labels (positive/negative/neutral)
├── README.md # Project documentation


- Sentiment_analysis.ipynb: 
  This is the main script that:
  - Loads and preprocesses the dataset
  - Splits the data into training and testing sets
  - Trains a Naive Bayes classifier using a text vectorizer
  - Accepts custom user input and predicts sentiment

- Sentiment_analysis.csv:
  A CSV file containing two columns:
  - `text`: The review or opinion statement
  - `sentiment`: The labeled sentiment (e.g., positive, negative, neutral)

- README.md:  
  Explains the purpose, structure, and usage of the project.

  ## Requirements

- Python 3.x
- pandas
- scikit-learn


## How to Run
- A table providing the sentimental analysis will be displayed. 
- You will be prompted to enter a custom text. The model will analyze it and print the predicted sentiment.
