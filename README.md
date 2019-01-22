## Natural Language Processing - Sentiment Analysis

This repository contains three notebooks which each create a different NLP model to predict the sentiment (positive or negative) of a movie review.

The dataset are IMDB movie reviews and can be found [here](https://www.kaggle.com/utathya/imdb-review-dataset).

##### Part 1
Pretrained work embeddings with 100 dimensions are used. The input to the network is the average of the word embeddings of the review.

The trained model achieves an AUC of 0.88 on the test dataset.

As well as training a model, part one shows some of the fun things you can see when exploring word embeddings. For example, woman + king - man = queen.

[](queen-to-king.PNG)

You can see my portfolio [here](http://benjaminphillips22.github.io).