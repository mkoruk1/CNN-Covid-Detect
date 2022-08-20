Introduction:
Cnn is one of the main algorithms of deep learning.
It became very import part of computer vision. Most commonly used for image classification, object detection etc...

The architecture of CNN is made of 3 layers.
1- Input 2-Hidden Layers 3-Classification

Input is the data source. Mostly images.

Hidden layers are also divided into 3 subcategories:
1- Convolution 2-Pooling 3-Flattening

1-Convolution
In Convolutional layers filters (kernel) are used to find features from the inputs.
The convolutional process is done by shifting the filter on the image. Conflicting numbers are multiplied.
The numbers obtained as a result of multiplication are added to the feature map matrix.
After features are found, relu function is applied to get rid of negative values.

2-Pooling
The purpose of pooling layer is to reduce the spatial size of the input image in order to reduce the required number of computations.
The size decreases but none of the features are get effects from that. Most of the important features still remains same.

3- Flattening
Converting the matrices resulting from the convolution and pooling into vectors consisting of n rows and 1 columns.
And then this output is fed to artificial neural networks as input.

Result:

The accuracy of the model is 91 percent, which is pretty good.
To test the model, the model was provided with a picture of liver, one with a corona and the other with a healthy lung, and the model correctly predicted which of the pictures was healthy or not.