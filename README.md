# DNN_MNIST

Basic deep neural network in Tensorflow to classify the MNIST images.  This network architecture:
- 3 hidden layers
- Each layer (except for output layer) has batch normalization and dropout
- using Elu activation function
- xavier weight initialization

Before adding dropout, the network scored ~ %97 on the test data, after adding dropout it scored ~ %91
