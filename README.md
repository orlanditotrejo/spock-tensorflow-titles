# spock-tensorflow-titles

TensorFlow on titles and subjects of scientific papers across multiple disciplines. Dataset contains
approximately 13100 entries.

This directory contains a notebook where a recurrent neural network is 
used to identify disciplines from journal titles. Using a RNN is useful and more 
accurate since information about the sequence of the words is used. For this project, 
a dataset of titles (features) and subjects (labels) from scientific papers is used 
for the RNN training. This RNN uses an embedding layer for a more efficient 
representation of the vocabulary. This new representation of words from the embedding 
layer is then passed to Long-Short Term Memory (LSTM) cells, which add recurrent 
connections.


