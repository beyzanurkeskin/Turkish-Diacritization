# Project Title

## Description
This project focuses on language processing tasks using a BiLSTM neural network. The tasks include data preprocessing, model architecture design, training, and prediction.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Predictions](#predictions)

## Installation
This project can be run on Google Colab or any Python environment with the required libraries installed. Ensure you have the following installed:
- Python 3
- Pandas
- Numpy
- Tensorflow
- Keras
- Google.colab (if running on Google Colab)

## Usage
1. Clone the repository.
2. Ensure your Google Drive is mounted on Colab or adjust file paths accordingly.
3. Run the provided code cells in order.

## Training
1. Data preprocessing:
    - Mount Google Drive and load necessary datasets.
    - Merge and preprocess the datasets.
    - Perform ASCII conversion on the text data.
2. Model architecture:
    - Implement a BiLSTM neural network using TensorFlow/Keras.
    - Define the architecture including embedding, bidirectional LSTM layers, and output layer.
3. Train the model:
    - Compile the model with appropriate optimizer and loss function.
    - Train the model on the prepared data.
4. Save the model:
    - Save the trained model for later use.

## Predictions
1. Load the test dataset.
2. Tokenize and preprocess the test data.
3. Use the trained model to make predictions on the test data.
4. Display the predicted sentences along with the original ones.


