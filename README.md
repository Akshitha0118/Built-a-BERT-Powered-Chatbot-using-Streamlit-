# Built-a-BERT-Powered-Chatbot-using-Streamlit

A simple AI-powered chatbot built using BERT (Bidirectional Encoder Representations from Transformers) and Streamlit.
This project uses semantic similarity to understand user queries and respond intelligently.

## 🚀 Project Overview

This chatbot leverages the pre-trained bert-base-uncased model to generate contextual embeddings for user input and predefined questions.
It compares them using cosine similarity and returns the most relevant response.
Unlike traditional rule-based chatbots, this model understands the meaning of the sentence rather than just matching keywords.

## 🛠️ Technologies Used

Python

PyTorch

Streamlit

Transformers (Hugging Face)

Scikit-learn

## 🧠 How It Works

Load BERT tokenizer and model

Generate embeddings for predefined questions

Convert user input into embedding

Compute cosine similarity

Return the most similar response (based on threshold)


## 📸 Features

✅ Semantic understanding using BERT

✅ Cosine similarity matching

✅ Simple and clean Streamlit UI

✅ Custom background styling

✅ Fast response with cached model
