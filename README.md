# Face-Mask-Detection-using-Convolutional-Neural-Network-CNN

Face Mask Detection system using a Convolutional Neural Network (CNN) in Python using the TensorFlow and Keras libraries. 


Here's a summary of what I've done:

Imported Libraries: You imported necessary libraries such as os, numpy, matplotlib, PIL, tensorflow, and others.

Loaded Image Files: You loaded file names for images with and without masks from specified paths.

Data Exploration: You displayed some file names and checked the number of images for each class.

Created Labels: You created labels for images with masks (1) and without masks (0).

Image Processing: You resized and converted the images to numpy arrays, and then scaled the pixel values.

Data Split: You split the data into training and testing sets.

Built CNN Model: You created a CNN model using the Keras Sequential API with convolutional layers, max-pooling layers, flatten layer, dense layers, and dropout layers.

Model Compilation: You compiled the model using the Adam optimizer and sparse categorical crossentropy loss.

Model Training: You trained the model using the training data and validated it on a subset.

Model Evaluation: You evaluated the model on the test set and printed the test accuracy.

Plotted Training History: You plotted the training and validation loss as well as accuracy over epochs.

Prediction Function: You implemented a function to predict whether a person is wearing a mask or not using the trained model. The function reads an input image, preprocesses it, and makes a prediction.

Prediction Example: You demonstrated the use of the prediction function on a user-provided image.
