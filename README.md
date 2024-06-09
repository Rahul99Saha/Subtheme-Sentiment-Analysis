
# Subtheme Sentiment Analysis

Sentiment Analysis using BERT
The task is to develop an approach that identifies subtheme sentiments in reviews using a BERT model. This README provides an overview of the project, including setup instructions, an explanation of the approach, and how to run the code.

## Project Description
The task is to analyze customer reviews to identify subtheme sentiments. Each review can contain multiple sentiments related to different aspects of the service. For instance, a review might express a positive sentiment towards the service but a negative sentiment towards wait time. This project uses a BERT model to perform this sentiment analysis.

## Approach
Tokenize the reviews using BERT tokenizer.
Label the subthemes based on predefined categories (positive or negative sentiment).

## Model
Use a pre-trained BERT model from Hugging Face.
Fine-tune the model on the dataset with labels for subtheme sentiments.
## Training
1.Split the dataset into training and validation sets.
2.Use Trainer from transformers for training the model with specified hyperparameters.
## SetUp
Prerequisites
1.Python 3.6+
2.PyTorch
3.transformers library
4.scikit-learn
5.pandas
6.numpy
