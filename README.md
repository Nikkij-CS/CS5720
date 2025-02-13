# Neural Network and Deep Learning

This project explores essential deep learning concepts using TensorFlow, including tensor manipulations, loss functions, model training with different optimizers, and performance tracking using TensorBoard. It demonstrates key techniques for reshaping tensors, comparing loss functions, optimizing models, and visualizing training trends. The code is divided into four sections, each addressing a different deep learning task using TensorFlow and Keras.

__1. Tensor Manipulations & Reshaping__
Creates a random tensor of shape (4,6).
Finds its rank and shape using TensorFlow functions.
Reshapes it to (2,3,4) and transposes it to (3,2,4).
Broadcasts a smaller tensor (1,4) to match the larger tensor and adds them.
Explains broadcasting, which allows TensorFlow to automatically expand dimensions.

__2. Loss Functions & Hyperparameter Tuning__
Defines true values (y_true) and model predictions (y_pred).
Computes Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE) losses.
Modifies predictions slightly to observe how loss values change.
Plots a bar chart comparing MSE and Cross-Entropy losses using Matplotlib.

__3. Training a Model with Different Optimizers__
Loads the MNIST dataset (handwritten digit recognition).
Builds and trains two simple neural networks:
-One using Adam optimizer.
-One using SGD optimizer.
Compares training and validation accuracy trends for both optimizers.
Plots accuracy curves to visualize Adam vs. SGD performance.

__4. Training a Neural Network and Logging to TensorBoard__
Loads and preprocesses the MNIST dataset.
Trains a simple neural network with TensorBoard logging enabled.
Visualizes training/validation accuracy and loss in TensorBoard.


