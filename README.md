# Smartchatbot-using-Python
A simple AI-based chatbot built using TensorFlow and NLTK. It classifies user inputs into predefined intents using a trained neural network and responds accordingly. Includes training data, model, and scripts for both training and real-time interaction.

# 🤖 Chatbot using Python, TensorFlow, and NLTK

This project is a simple AI-based chatbot built with Python, TensorFlow, and NLTK. It uses a neural network to classify user inputs into predefined intents and provides contextually relevant responses. The training data is defined in a structured `intents.json` file.

## 🧠 Features

- Natural Language Processing (NLP) using NLTK
- Intent classification with a deep neural network (Keras + TensorFlow)
- Real-time interaction with dynamic responses
- Bag-of-Words model for input vectorization
- Easily extendable by editing `intents.json`

---

## 📁 Project Structure

chatbot/
│
├── intents.json # Intent patterns and responses
├── train_chatbot.py # Preprocessing, model training and saving
├── chatbot_model.h5 # Saved trained model
├── words.pkl # Pickled vocabulary list
├── classes.pkl # Pickled class (intent) list
└── chat.py # Chat interface for real-time input and prediction


