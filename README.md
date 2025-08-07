# MNIST-Neural-Network-from-scratch-using-only-Numpy
This a two layered Neural Network created using math and use of `numpy` as a package

The two layered neural network consits of the following:
- `Input layer` or the 0th layer
- `Hidden layer` or the first layer
- `Output layer` - Y.

The objective of this Neural network is to train it on a handwritten grayscale digit images 
for the network to be able to recognise and predict it correctly.

The MNSIT dataset was used to train the Neural Network.

The MNSIT database consists of images of 784 pixels with the dimensions of 28 x 28, these 
are used to train this two layered Neural Network.

# Approach to build the Neural Network using Numpy:
- Before we delve into the details of it lets make sure of few notations :

    `m` - stands for training images.

    `T` - Transpose of a matrix --> i.e row's are now turned to columns in a new matrix.

    `A` - The activation output of a layer - i.e the values after applying the activation function to `Z`

    `W` - weights of the neural network -- first layer.

    `b` - biases that we add to when computing the parameters of the neural network.

    `Z` - unactivated layer/layers of the neural network. This is where you apply the weights and biases.

    refers to the linear combinations of weights and inputs before applying an activation function.

    `X` - is the input data of shape 784 x m (m = number of samples).

    `g` - is the activation function.

    `Y` - The exact answer the user want's the model to predict.

- Now there are parts of training and building this neural network, the following was done to train and build the network :

- `Forward Propogation`

    -On a high level, forward propogation in this case is for  the    network to make a guess.
    Like taking an image and run it through the network to compute the expected output and compare.

    -We can say `forward propogation` as the decision making pipeline.

    -So in our case, we give input as image pixels , multiply + add,  where each neuron processes the input with weights and biases.

    -To this we add an activation function like ReLU or softmax to apply the logic.

    -Then it proceeds to pass the results  forward to the next layer.

    














