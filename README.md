# Chatbot NLP

This repository contains code and resources for building an intelligent chatbot for human psychology.

## Project Overview

This project involves creating a chatbot that can interact with customers and answer their queries about car models, services, and more. The chatbot uses a pre-trained machine learning model to classify user intents and provide appropriate responses.

## Features

- **Intent Classification**: The chatbot can classify user inputs into predefined intent categories.
- **Dynamic Responses**: Provides responses based on the classified intent.
- **Web Interface**: A simple web interface for interacting with the chatbot.

## Project Structure

- **`intents.json`**: Contains the dataset with patterns and corresponding intent tags used for training the model.
- **`texts.pkl`**: Pickled file containing the vocabulary (unique lemmatized words) used for model training.
- **`labels.pkl`**: Pickled file containing the intent tags (classes) for the model.
- **`model.h5`**: Trained Keras model saved after the training process.
- **`app.py`**: Flask application to serve the chatbot and interact with users through a web interface.
- **`templates/index.html`**: Basic HTML template for the chatbot web interface.

