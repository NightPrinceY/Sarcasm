# Sarcasm Detection Model

## Project Overview

This project aims to develop a machine learning model capable of detecting sarcasm in textual data, specifically utilizing headlines. By understanding sarcasm, the model enhances the capability of natural language processing applications in accurately interpreting user sentiments and emotions.

## Objectives

- To classify text as sarcastic or not sarcastic using a machine learning model.
- To preprocess text data for effective training and evaluation.
- To visualize model performance through accuracy and loss metrics.

## Dataset

The dataset used for this project consists of sarcastic and non-sarcastic headlines in JSON format. It is obtained from a public dataset available at [TensorFlow](https://storage.googleapis.com/tensorflow-1-public/course3/sarcasm.json).

## Technologies Used

- Python
- TensorFlow
- NumPy
- Pandas
- Matplotlib

## Model Architecture

The model is constructed using a sequential neural network with the following layers:

1. **Embedding Layer**: Converts words into dense vector representations.
2. **Global Average Pooling Layer**: Averages the feature maps from the embedding layer to reduce dimensionality.
3. **Dense Layer**: Fully connected layer with ReLU activation for non-linearity.
4. **Output Layer**: Sigmoid activation function for binary classification.
