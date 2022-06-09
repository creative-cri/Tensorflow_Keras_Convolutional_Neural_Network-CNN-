# Tensorflow_Keras_Convolutional_Neural_Network-CNN-
Tensorflow_Keras_Convolutional_Neural_Network(CNN)
Steps:

First, import keras and load the dataset.

Import matplotlib and see what the data looks like

Next, we need to break the data down so that the neural network can digest it easier.

Then, we convert the y values (numbers) into ones and zeros, making each number categorical. This is called one-hot encoding. Without it, the neural network might categorize numbers based on how they are related numerically rather than how they look. To learn more about one-hot encoding, click here https://www.youtube.com/watch?v=v_4KWmkwmsU

It's time to build the neural network. Each layer is a different type of neuron. Read here how each of them work. https://keras.io/api/layers/core_layers/

Next, we need to train the network. Feel free to switch around the type optimizer, number of epochs, or batch size. Depending on how fast your GPU is, this model can take some time to train. On the colab GPU, one epoch takes around 2 minutes.

Finally, run the model on the test data and print the results. The first number is the loss and the second number is the accuracy out of 1.
