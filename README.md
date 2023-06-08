# Introduction to Natural Language Processing 2 Lab03

Auhors : 
- Jonathan Poelger
- Ethan Machavoine
- Aurelien Rouxel
  
## HuggingFace Transformers
This project implements a sentiment analysis model using the HuggingFace transformer library. The goal is to fine-tune a transformer model on the IMDB dataset and evaluate its performance on the test set.

## Dataset
The model is trained on the IMDB dataset, which consists of movie reviews labeled with sentiment (positive or negative). The dataset is split into training and testing sets, and it is used to train and evaluate the sentiment analysis model.

## Model Architecture
The sentiment analysis model is based on transformer neural network architecture, leveraging pre-trained models such as DistilBERT, BERT, RoBERTa, or DeBERTa. These models have been fine-tuned on the IMDB dataset to classify the sentiment of text data.

## Steps
1. **Fine-tuning**: The model is fine-tuned on the training data using the chosen pre-trained model from HuggingFace's model hub. The model is trained for at least one epoch, and the notebook used for training includes relevant comments explaining the process.
2. **Evaluation**: The fine-tuned model is evaluated on the test data in terms of accuracy. The accuracy metric is used to measure the model's performance in correctly classifying the sentiment of the test reviews.
3. **Misclassified Samples**: At least two misclassified samples from the test set are analyzed to understand why the model could have made incorrect predictions. Factors contributing to misclassifications are discussed and explained.
4. **Advantages and Inconveniences**: A comparison is made between the sentiment analysis model based on transformers and the naive Bayes model implemented in the earlier part of the course. Additionally, the advantages and inconveniences of using the transformer model compared to a recurrent model like RNN or LSTM are discussed.
