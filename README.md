Neural Network for Occupation Prediction

This project aims to build a neural network to predict occupations based on various features like education, race, and sex. The model uses a simple feedforward neural network architecture implemented using TensorFlow and Keras.

Development:
Data Preparation:
Null values are removed and all categorical features are one hot encoded.

Training the Model:

The neural network model is defined, optimized and compiled. It uses reLu activation functions in the hidden layers and a softmax function in the output latyer. It is optimized with stochastic gradient descent, using the Adam algorithm.
The model is trained for a specified number of epochs.

Evaluating the Model:

Accuracy and loss are plotted to visualize the model's performance.
