"# toxic-comment-classification" 
Solution for the competition: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

current position: top 20% (improving day by day)

approach:
1. Used Glove 200D word embeddings trained on negative tweets.
2. Sequence classification using Bi-directional GRUs, followed by convolutional and dense layers.


Results:
current ROC-AUC: 0.9829
