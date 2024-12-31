# MNIST digit classification

This is a simple example of a neural network 
that classifies handwritten digits from the MNIST dataset.
Following the book 
["Neural Networks and Deep Learning"](neuralnetworksanddeeplearning.com) 
by Michael Nielsen, I understood how a neural network works at
it's core.

This particular network is based on a mini-batch stochastic
gradient descent algorithm.
In the book the network is trained using one hidden layer of 
30 neurons, however from my testing I have observed an increase
in accuracy of about 0.5% when utilizing one hidden layer of 50
neurons.