# Activation Function

In a deep neural network, activation functions play a crucial role in determining the output of a neuron and enabling the backpropagation algorithm for updating weights during training. This readme file provides an overview of activation functions and references to different implementations available on GitHub.

## Activation Functions

1. **Sigmoid Function**: The sigmoid function maps the input to a range between 0 and 1, making it suitable for binary classification tasks. It has a smooth gradient but suffers from the vanishing gradient problem.
   
2. **ReLU (Rectified Linear Unit)**: ReLU sets negative values to zero and keeps positive values unchanged. It is widely used due to its simplicity and ability to mitigate the vanishing gradient problem. However, it suffers from the "dying ReLU" problem when neurons become inactive during training.

3. **Leaky ReLU**: Leaky ReLU is an improved version of ReLU that allows small negative values instead of setting them to zero. This modification helps address the dying ReLU problem.

4. **Tanh (Hyperbolic Tangent)**: Tanh function maps the input to a range between -1 and 1. It is zero-centered and provides stronger gradients than the sigmoid function, making it suitable for hidden layers.

5. **Softmax**: Softmax is commonly used in the output layer of a classification model. It converts the inputs into a probability distribution, enabling multi-class classification.

## GitHub Repositories

Here are some GitHub repositories that provide implementations of various activation functions:

1. [Activation Functions in TensorFlow](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/python/ops/nn_impl.py): TensorFlow's official repository contains the implementation of various activation functions in Python.

2. [Activation Functions in PyTorch](https://github.com/pytorch/pytorch/blob/master/torch/nn/functional.py): PyTorch's official repository includes a range of activation functions implemented in Python.

3. [Activation Functions in Keras](https://github.com/keras-team/keras/blob/master/keras/activations.py): The Keras library provides a collection of activation functions in Python.

Please note that the mentioned repositories may contain implementations for other functionalities as well, so navigate to the respective activation function sections or search within the repositories to find the specific implementations you are interested in.

Remember to check the licenses and documentation of each repository before utilizing the code in your own projects.

Happy coding and exploring the world of activation functions!
