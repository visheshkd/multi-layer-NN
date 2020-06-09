VISHESH KUMAR DWIVEDI

Objective : Create multi-layer neural networks using Tensorflow (without using
Keras) .
Programming Language : Python 3.7
IDE : ANACONDA 3(Spyder)

Methods Implemented :

add_layer - This is where you add a layer to the network. Note that this function adds a layer
after that last layer of the network. In other words this function appends a layer.

predict - Given array of inputs this method predicts array of corresponding outputs for the multilayer
network.

train - Given array of inputs, desired outputs as class indexes, and other parameters, this
method adjusts the weights using the partial derivatives of the loss function with respect to weights
and biases. Note that this method should implement batch training. You do not need to implement
regularization in this assignment.

get_weights_without_biases - Given the layer number. This function returns the weight matrix
for the given layer.

get_biases - Given the layer number. This function returns the biases for the given layer.

set_weights_without_biases - Given the layer number. This function sets the weight matrix for
the given layer.

set_biases - Given the layer number. This function sets the biases for the given layer.

calculate_percent_error - Given array of inputs and desired outputs as class indexes this
method calculates percent error.

calculate_confusion_matrix - Given array of inputs and desired outputs as class indexes array
this method calculates the confusion matrix