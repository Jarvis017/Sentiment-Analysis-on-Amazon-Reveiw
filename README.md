
## About the project

The models were trained on the Amazon Reviews for Sentiment Analysis dataset. 
The text data was pre-processed using a TF-IDF vectorizer. 
This project uses two deep learning models for sentiment analysis:
* Naive Bayes
* Bert
* Simple Neural Network


For Bert Implementation, there are two models. First, using Bert Pretrained model. Second, using Embedding layer of 
the Bert.

The review body and review headline are two of the most important parts of an Amazon review, and that they provide a lot of information about the reviewer's sentiment, So the neural network was trained on the TF-IDF vectors of the review body and review headline.

## Dataset

The dataset contains 850,000 Amazon reviews, each with a sentiment label. The lables partitioned into 3 classes:
* Positive
* Negative
* Neutral

 Dataset:
 https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Watches_v1_00.tsv.gz
