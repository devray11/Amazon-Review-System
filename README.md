# Sentiment Analysis on Amazon Alexa Reviews

## NLP-Powered Sentiment Classification System

This repository contains a complete end-to-end project for analyzing customer sentiment on Amazon Alexa reviews. The system uses Natural Language Processing (NLP) and Machine Learning to classify reviews as 'Positive' or 'Negative'.

The project includes a data exploration and modeling pipeline, a backend API built with Flask to serve the ML models, and an interactive web application built with Streamlit for user interaction. The web app allows for both single review predictions and bulk predictions by uploading a CSV file, complete with visualizations of the results.

## Features

* **Sentiment Classification:** Classifies user-provided text (reviews) into 'Positive' or 'Negative' sentiment.
* **NLP Preprocessing:** Implements a standard NLP pipeline including text cleaning, stopword removal, and stemming using NLTK.
* **Machine Learning Models:** Trained and compared multiple models, including Random Forest, Decision Tree, and XGBoost, for high accuracy.
* **Interactive Web App:** A user-friendly interface built with Streamlit.
* **Single Prediction:** A text area to input a single review for instant sentiment analysis.
* **Bulk Prediction:** Allows users to upload a CSV file of reviews and receive a full analysis with predictions for each entry.
* **Data Visualization:** Automatically generates pie charts and bar charts (using Plotly) to show the distribution of sentiments in bulk-predicted data.

## Technologies Used

* **Frontend / Web App:** Streamlit
* **Backend API:** Flask
* **Machine Learning:** Scikit-learn (RandomForestClassifier, DecisionTreeClassifier), XGBoost
* **NLP:** NLTK (PorterStemmer, stopwords)
* **Data Processing:** Pandas, NumPy
* **Text Vectorization:** Scikit-learn (CountVectorizer)
* **Data Visualization:** Plotly Express

## Dataset

The model was trained on the "Amazon Alexa Reviews" dataset (`amazon_alexa.tsv`), which contains 3150 customer reviews for Amazon Alexa products, along with their ratings and feedback (1 for positive, 0 for negative).

