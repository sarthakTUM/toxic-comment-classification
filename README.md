"# toxic-comment-classification" 

Solution for the competition: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

current position: top 20% (improving day by day)

approach 1:
1. trained a simple MLP on document vectors obtained using SpaCy embeddings
2. download training set vectors from: 
3. download testing set vectors from:

approach 2:
1. Used Glove 200D word embeddings trained on negative tweets.
2. Sequence classification using Bi-directional GRUs, followed by convolutional and dense layers.


Results:
current ROC-AUC: 0.9829
