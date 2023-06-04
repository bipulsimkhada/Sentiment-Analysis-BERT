# Sentiment Analysis uning BERT

## BERT
Bidirectional Encoder Representations from Transformers (BERT) is a deep learning model developed by Google in 2018, which has become one of the most important models for natural language processing (NLP) tasks. BERT has achieved state-of-the-art results on a wide range of NLP tasks, including sentiment analysis, question answering, and natural language inference. It has become a widely used model in the NLP community and has been the basis for many subsequent models and architectures.

## Hugging Face
HuggingFace has developed several popular tools, including Transformers, Tokenizers, Datasets, and Trainer. The Transformers library provides access to a wide range of pre-trained language models, including BERT, GPT-2, and T5. Tokenizers provide efficient and customizable text tokenization, and Datasets provide easy access to common NLP datasets.

## Libraries 
* Keras
* Transformers
* numpy
* pandas
* os
* re
* io
* pathlib

## Tool
* Google Colab
* Google Drive

## Dataset
IMDB dataset

## BERT for Sentiment Analysis
In this project, we used the dataset containing IMDB reviews and labeled sentiment. We trained our model for sentiment analysis from the IMDB review dataset with 0 being negative and 1 being positive. The dataset is available with tensorflow library. Here are the steps involved:
* Intall Transformers and datasets library
* Import IMDB dataset. Dataset contains 25,000 of test and 25,000 of train data.
* Import "Bert Base Uncased" model and Bert Tokenizer to clean data, and tokenize data and add necessary padding. 
* Use Roberta Classifer model
* Compile and train the model

## Model Evaluation
Loss: 0.1987 <br>
Accuracy: 92.66%

Validation Loss: 0.3285 <br>
Validation Accuracy: 86.75%
