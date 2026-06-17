# IMDB-Sentiment-Analysis

Deep Learning-based IMDB Movie Review Sentiment Analysis using RNN, LSTM, GRU, and Bi-LSTM models with performance comparison and evaluation.

## Project Overview

This project performs sentiment analysis on IMDB movie reviews using deep learning techniques. The goal is to classify movie reviews as either positive or negative based on the textual content of the reviews.

## Dataset

The IMDB Movie Reviews Dataset was used for this project. The dataset contains 50,000 movie reviews labeled as positive or negative sentiments.

* Total Reviews: 50,000
* Classes: Positive, Negative
* Dataset Source: Kaggle IMDB Dataset

## Data Preprocessing

The following preprocessing steps were performed:

* Tokenization of text reviews
* Vocabulary size limitation
* Sequence padding
* Train-test split

## Models Implemented

1. Simple RNN
2. LSTM (Long Short-Term Memory)
3. GRU (Gated Recurrent Unit)
4. Bidirectional LSTM (Bi-LSTM)

## Performance Evaluation

The models were evaluated using Accuracy, Precision, Recall, F1-Score, and AUC metrics. A comparison was performed to determine the best-performing architecture for sentiment classification.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

## Project Files

* IMDB_Sentiment_Analysis.ipynb
* requirements.txt

## Conclusion

This project demonstrates the application of deep learning techniques for natural language processing and sentiment analysis. Different recurrent neural network architectures were compared to analyze their effectiveness in classifying movie reviews.
