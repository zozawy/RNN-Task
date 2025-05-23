
Sentiment Analysis on Movie Reviews Using RNN
Description
This project implements a deep learning model to classify movie reviews from the IMDB dataset as positive or negative. It uses a Recurrent Neural Network (RNN) architecture to analyze text sentiment with high accuracy.

The model preprocesses raw text reviews, converts them into sequences, pads them to a fixed length, and then trains an embedding + RNN model to predict sentiment.

Features
Preprocessing of raw movie review texts

Tokenization and padding of sequences

Embedding layer for word representation

Recurrent Neural Network layer to capture sequential patterns

Dropout for regularization

Binary classification (positive vs negative)

Interactive user input for sentiment prediction on new reviews

Technologies Used
Python

TensorFlow & Keras

pandas, NumPy

scikit-learn (for train-test split)

Matplotlib & Seaborn (for visualization, if needed)

Dataset
IMDB Movie Reviews Dataset (available publicly and included as CSV)
Dataset contains 50,000 labeled reviews (positive or negative sentiment)
