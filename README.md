# Fake News Detection Model

In case of issues with displaying the .ipynb file on GitHub, please use nbviewer to view the file : [nbviewer link](https://nbviewer.org/github/AcidicArmadillo/Fake-news-detection/blob/master/Fake_News_Detection.ipynb)

## Overview

This project presents a Deep Learning model for detecting potentially fake news headlines. The model uses the base BERT model for Transfer Learning and has been fine-tuned on a corpus of tens of thousands of news headlines and articles - both real as well as fake. The model bases its predictions using linguistic cues and text patterns found in news headlines in English.

## Features

- **Text Classification** : The model is designed to classify any provided news headline as True or Fake.
- **Transfer Learning** : Utilizes transfer learning to make use of base BERT model and fine-tunes it to capture the linguistic cues and text patterns to generate a probabilistic result, enabling news headlines to be classified as True or Fake.
- **Corpus** :  The training corpus consists of a huge number of real as well as fake news headlines in English, providing a diverse context for the model to learn from.

## Usage

1. **Training the model** : Run all the cells except the last two sections (Model Performance and Predictions) to train the model.
2. **Prediction** : Run the cells in the Prediction section to classify a news as Fake or True.
3. **Model Performance** : Run the cells in the Model Performance section to view the Classification Report of the model.


Feel free to explore the performance of the model and to enhance and improve upon it. 
