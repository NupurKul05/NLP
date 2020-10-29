# NLP
# Sentiment Classification
The task of classifying sentiments of texts (for example movie or product reviews) has high practical significance in online marketing as well as financial prediction. This is a non-trivial task, since the concept of sentiment is not easily captured.
For this assignment you have to use the Amazon Food Review (https://www.kaggle.com/snap/amazon-fine-food-reviews) dataset.

The task is to try out multiple models in ascending complexity, namely:
1.	TFIDF + classical statistical model (eg. RandomForest)
2.	LSTM classification model
3.	LSTM model, where the embeddings are initialized with pre-trained GloVe vectors
4.	fastText model
5.	BERT based model (you are advised to use a pre-trained one and finetune, since the resource consumption is considerable!)

You are allowed to use any library or tool, though the Keras environment, and some wrappers on top (ie. Ktrain) make your life easier. The performance metrics are exactly those given in the Kaggle contest.

