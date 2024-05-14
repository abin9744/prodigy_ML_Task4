# prodigy_ML_Task4
# Hand Gesture Recognition Model
This repository contains code for developing a hand gesture recognition model using the Sign Language MNIST dataset. The model is built using TensorFlow and trained to recognize hand gestures from images.

# Dataset
The Sign Language MNIST dataset consists of 28x28 grayscale images of hand gestures representing letters from the American Sign Language alphabet. Each image is labeled with a corresponding letter.

# Dataset Link: Sign Language MNIST

# Model Architecture
The hand gesture recognition model is built using a convolutional neural network (CNN) with the following architecture:

Convolutional Layer 1: 32 filters, kernel size (3x3), ReLU activation
MaxPooling Layer 1: Pool size (2x2)
Convolutional Layer 2: 64 filters, kernel size (3x3), ReLU activation
MaxPooling Layer 2: Pool size (2x2)
Flatten Layer
Dense Layer: 128 units, ReLU activation
Output Layer: 26 units (corresponding to 26 letters), softmax activation
Model Evaluation
The model is trained using the training data and evaluated on the testing data. Performance metrics such as accuracy, confusion matrix, and classification report are generated to assess the model's effectiveness in hand gesture recognition.
