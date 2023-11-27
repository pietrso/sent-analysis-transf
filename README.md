# Sentiment Analysis on Tweets
The scope of this project is to understand how to use the Hugging Face library at a deeper level with a custom dataset.
The task is a Sentiment Analysis on [Airline Tweets](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) using a DistilBert Transformer. The model has been Fine-Tuned on the dataset and the strong imbalance of the data has been tackled modifying the class weights in the loss function.

## Results on imbalanced data
![imbalanced](/imbalanced.png)

## Results setting class-weights
![balanced](/balanced.png)
