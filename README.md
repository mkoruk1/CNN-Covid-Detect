# CNN-Covid-Detect
A convolutional neural network was used to predict if the person has a corona or not based on the lung image.

# Dataset
https://www.kaggle.com/datasets/akkinasrikar/covid19-xray-images-using-cnn
# Introduction

![CNN structure](https://user-images.githubusercontent.com/62452267/185764522-6e457b70-3a2a-4833-bf50-84f284be68de.jpeg)

Cnn is one of the main algorithms of deep learning.
It became a very important part of computer vision. Most commonly used for image classification, object detection, etc...
The architecture of CNN is made of 3 layers.
1- Input 2-Hidden Layers 3- Classification

Input is the data source. Mostly images.
Hidden layers are also divided into 3 subcategories:
1- Convolution 2-Pooling 3-Flattening

Convolution Layers:
In Convolutional layers filters (kernel) are used to find features from the inputs.
The convolutional process is done by shifting the filter on the image. Conflicting numbers are multiplied.
The numbers obtained as a result of multiplication are added to the feature map matrix.
After features are found, relu function is applied to get rid of negative values.

Pooling Layer:
The purpose of the pooling layer is to reduce the spatial size of the input image in order to reduce the required number of computations.
The size decreases but none of the features get effects by that. Most of the important features still remain the same.

Flattening Layer:
Converting the matrices resulting from the convolution and pooling into vectors consisting of n rows and 1 column.
And then this output is fed to artificial neural networks as input.

# Results
The accuracy of the model is 91 percent, which is pretty good.
To test the model, I provided 2 lung images that were not seen before by the model. One of the pictures was of a healthy liver and the other of a liver with a corona. And the model correctly predicted which of the pictures was healthy or not.
