# TensorflowMNIST
This repo is just meant for practicing small neural network models with tensorflow on mnist datasets.  

## mnsit_tf.py
This is just a simple neural network model with 4 hidden layers. One can easily change the number of hidden layers and the number of neurons. I have experimented with a lot of hyper parameters. I will list the best two results I got from this model. Truly speaking this is a lame model by todays standards, nevertheless a good point to start.

* optimizer: Adam Optimizer with default learning rate.
* loss function: softmax_cross_entropy_with_logits

### Results
 * Hidden Layers: 3, 
 * Neurons: [500. 500, 500],
 * Activation Function: [relu, relu, relu],
 * Batch size: 40,
 * epochs: 70, 
 * Accuracy: 0.9737
 

 * Hidden Layers: 4, 
 * Neurons: [700. 700, 700, 700],
 * Activation Function: [relu, relu, relu, relu],
 * Batch size: 100,
 * epochs: 70, 
 * Accuracy: 0.9738


