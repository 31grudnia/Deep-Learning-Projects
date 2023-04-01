# Breast Cancer Predictiom

This code is implementing a neural network using **TensorFlow** to predict if a breast cancer tumor is malignant or benign based on various features. The dataset used is the breast cancer Wisconsin (Diagnostic) dataset from scikit-learn.

The code first loads the dataset, converts it to a Pandas DataFrame, and splits it into features and labels. It then performs data preprocessing by standardizing the features using the StandardScaler from scikit-learn.

Next, it sets up a neural network with two hidden layers and an output layer with two nodes using the Sequential API in Keras. It compiles the model by specifying the optimizer, loss function, and evaluation metrics. It then trains the model using the fit method, specifying the training data, validation split, and number of epochs.

After training the model, the code plots the accuracy and loss for both the training and validation data. It then evaluates the model's performance on the test data and prints the accuracy.

Finally, it predicts the class label for a new input using the trained model and prints whether the tumor is malignant or benign.
