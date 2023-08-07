# NLP-sentiment-analysis-BERT


## Introduction
This repository contains code and resources to perform sentiment analysis on Google PlayStore reviews using BERT Transformers with PyTorch. Basically the project is about building a machine learning model that can predict the sentiment of a given review as positive, negative.

## Dataset
The dataset used for training and testing the model is a collection of Google PlayStore reviews labeled with their corresponding sentiments (positive, negative). The dataset is extracted from kaggle website where the dataset has consist of ratings from 0 to 5, sentiment function is used to create a sentiment column where it classifies the reviews into positive (1) or negative (0).

## BERT Transformers and PyTorch
BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained transformer-based model developed by Google. It is known for its excellent performance in natural language processing tasks, including sentiment analysis. We will use the transformers library in PyTorch to leverage the power of BERT for our sentiment analysis task.

## Model Performance
The trained BERT-based model achieved an accuracy of 75.47 percent on the test dataset. The model architechture consist of BERT transformer which is divided into input layer, attention mask layer and finally the output layer.

## Conclusion
This repository is a simple model of sentiment analysis of Google PlayStore reviews using BERT Transformers with PyTorch. Experimenting with different tokenization strategies, learning rates, and batch sizes to improve the model's accuracy. We can use optuna to get the optimized hyperparameters.




