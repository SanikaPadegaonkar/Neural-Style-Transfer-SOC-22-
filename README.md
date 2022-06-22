# Neural-Style-Transfer-SOC-22-
Part 1: Data preprocessing/ Getting familiar with data
Data Sources: 
1. https://github.com/yursky/art-of-text/tree/master/data/kaggle 
PS: Given a sentence predict the author based on style 
The model learns to predict the style
Task 1: Use the above data to train a multiclass style classification model
Carry out exploration of the data as mentioned in:
https://www.kaggle.com/code/bsivavenu/lsa-model-on-spooky-author-data?scriptVersionId=7965809 
Things to use: Hugging Face library (How to train a text classifier using HF)
Strategy; Divide train-set into 80:20 train-validation split and provide validation accuracy
Test on the test.csv: And show the prediction on the test set during the next meeting


2. Comparison with RNN baseline:
To learn about RNNs and LSTMS:
http://karpathy.github.io/2015/05/21/rnn-effectiveness/  
https://colah.github.io/posts/2015-08-Understanding-LSTMs/ 
https://www.youtube.com/watch?v=QvkQ1B3FBqA 
Code (you can get many more examples of RNNs for text classification on web)
https://towardsdatascience.com/multi-class-text-classification-with-lstm-1590bee1bd17 :
https://towardsdatascience.com/lstm-text-classification-using-pytorch-2c6c657f8fc0 

Task:
Use data in task 1 to train an RNN (or LSTM) based classifier 
Carry out comparison with hugging face baseline

Tip: Open the medium articles in incognito tab
