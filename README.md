# 🎬 IMDB Movie Review Sentiment Classification (Simple RNN)  
This project implements a **Recurrent Neural Network (RNN)** to classify IMDB movie reviews into **positive** and **negative** categories. It demonstrates how sequential models can capture sentiment patterns in text using the **TensorFlow/Keras** framework. The trained model (`simple_rnn_imdb.h5`) is included for quick predictions.  

## 📂 Project Structure  
Deep_learning/
├── main.py # Script to run the model / app
├── simplernn.ipynb # Notebook for training & evaluation
├── prediction.ipynb # Notebook for testing model predictions
├── simple_rnn_imdb.h5 # Trained RNN model
├── requirements.txt # Dependencies
└── README.md # Documentation

Model Architecture

Embedding Layer → Word representation

Simple RNN Layer → Sequential pattern learning

Dense Layer → Fully connected output

Sigmoid Activation → Binary classification (Positive / Negative)

