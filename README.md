# Handwritten Character Recognition Web App

This project implements a Deep Learning Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify handwritten digits (0–9) using the MNIST dataset. It features an interactive Flask web interface for real-time digit drawing and prediction.

## Features
- **CNN Architecture**: 2D Convolutional layers with Max Pooling, Flattening, Dense layers, and Dropout regularization.
- **Web Interface**: Integrated HTML5 drawing canvas powered by a Flask backend for instant predictions.
- **Data Preprocessing**: Image resizing (28x28 grayscale) and normalized pixel scaling.

## Setup & Execution
1. Open `Handwritten_Character_Recognition.ipynb` in Google Colab.
2. Run all code cells to train the network and launch the web server.
3. Access the generated proxy URL to draw digits and view live predictions.
