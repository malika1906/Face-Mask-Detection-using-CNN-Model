# Face-Mask-Detection-using-CNN-Model

A Convolutional Neural Network model has been built to detect whether a person is wearing a mask on their face or not.

This Deep Learning project has been done using Tensorflow and Keras, using Conv2D model, on a Kaggle dataset for Face Mask Detection.
This dataset consists of two files 'With Masks' and 'Without Masks'. having total 7553 images. These images have been used for training and testing the neural netwrk model. Image processing have been done to resize images and convert them into numpy arrays, and scaling them. 
2 dense layers of 128 and 64 neurons respectively is used, with the Relu activation function. The output layer consists of 2 neurons, because the goal is that of a binary classifier, and the sigmoid activation fucnction is implemented. The model is compiled with loss function and optimiser, and it is finally trained over the training data over 5 epochs.

Upon model evaluation, the training accuracy comes to be 92.16% and test accuracy is 91.26%.
Using matplotlib.pyplot, graphs have been plotted to display the training and validation loss and accuracy, respectively.
A predictive system is built in order to implement this model by feedim=ng any input image by user, and getting the oprediction outcome, whether the person in image is wearing a mask or not. The model prediction is accurate and successful.
