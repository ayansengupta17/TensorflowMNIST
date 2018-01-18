# TensorflowMNIST
This repo is just meant for practicing small neural network models with tensorflow on mnist datasets.  

## mnsit_tf.py
This is just a simple neural network model with 4 hidden layers. One can easily change the number of hidden layers and the number of neurons. I have experimented with a lot of hyper parameters. I will list the best two results I got from this model. Truly speaking this is a lame model by todays standards, nevertheless a good point to start.

* optimizer: Adam Optimizer with default learning rate.
* loss function: softmax_cross_entropy_with_logits

### Results:
Best result with 3 hidden layers:
 * Hidden Layers: 3, 
 * Neurons: [500. 500, 500],
 * Activation Function: [relu, relu, relu],
 * Batch size: 40,
 * epochs: 70, 
 * Accuracy: 0.9737
 Best result with 4 hidden layers:
 * Hidden Layers: 4, 
 * Neurons: [700. 700, 700, 700],
 * Activation Function: [relu, relu, relu, relu],
 * Batch size: 100,
 * epochs: 70, 
 * Accuracy: 0.9738

I failed to cross the accuracy of 97% on test data.


## mnsit_tf_rnn.py
This is just a Recurrent Neural Network model with an LSTM in TensorFlow. This python file has both the models namely the simple neural network model with 4 hidden layers and the Recurrent neural network with LSTM.

* optimizer: Adam Optimizer with default learning rate.
* loss function: softmax_cross_entropy_with_logits

### Best Result:

* batch size: 128
* tile size: 28
* number of tiles: 28
* rnn size: 512
* epochs: 40 
* loss: 2.079
* Accuracy: 0.99
