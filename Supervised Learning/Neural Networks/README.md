# Neural Networks

A __Neural Network__ is a mathematical model composed of layers of artificial neurons. It consists of a set of weights, a bias, an activation function, and a loss function, and is a powerful function approximator. 

The __Perceptron__ learning algorithm is a classification algorithm that is often credited as the first neural network. In the Perceptron module in this directory, we implement the Perceptron learning algorithm for binary species classification using the [Iris](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html#sklearn.datasets.load_iris) data set.

The __Multilayer Perceptron__ (MLP) algorithm learns a function <img src="https://render.githubusercontent.com/render/math?math=f: \mathbb{R}^m \to \mathbb{R}^p"> for either classification or regression. An MLP has an input layer, output layer, and one or more hidden layers (which may be non-linear). In the Multilayer Perceptron module in this directory, we build a MLP for the [Fashion MNIST](https://keras.io/api/datasets/fashion_mnist/#load_data-function) dataset with an input layer containing 784 input nodes, 2 hidden layers, and an output layer containing 10 output nodes.  

--- 

### Software Requirements

The following libraries are required to run the attached code:

- [Matplotlib](https://matplotlib.org)
- [Pandas](https://pandas.pydata.org)
- [Numpy](https://numpy.org)
- [Sklearn](https://scikit-learn.org/stable/)
- [Tensorflow](https://www.tensorflow.org/api_docs/python/tf/keras)
- [Keras](https://keras.io/api/datasets/)
