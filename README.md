# MNIST Digit Classification

This code is implementing a neural network to classify handwritten digits from the MNIST dataset. It is using Keras and TensorFlow libraries for building and training the neural network. The code is first loading the MNIST dataset using the mnist.load_data() method and then splitting it into training and testing data. The images are then scaled by dividing each pixel value by 255 to normalize the data.

The neural network architecture consists of three layers - two hidden layers with 50 nodes each and a final output layer with 10 nodes (one for each digit from 0-9). The first layer is a Flatten layer, which flattens the input image into a 1D array. The activation function used in the hidden layers is the rectified linear unit (ReLU) and the final layer uses a sigmoid activation function.

The model is compiled with the adam optimizer, sparse_categorical_crossentropy loss function and accuracy metric. It is then trained on the training data for 10 epochs.

After training the model, it is evaluated on the testing data to calculate the loss and accuracy. The model is then used to make predictions on a sample image from the testing data, and the predicted label is compared with the actual label to check the model's performance.

Finally, the code downloads an image from a GitHub repository, resizes it, converts it to grayscale, and then predicts the digit using the trained model.
