# CNN BASED DIGIT CLASSIFIER

![](https://i.imgur.com/AA7t4sb.png)

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms.

The objective of the Convolution Operation is to extract the high-level features such as edges, from the input image. ConvNets need not be limited to only one Convolutional Layer.

![](https://i.imgur.com/evxdKt9.gif)


## Concepts involved

### Kernal
In the above demonstration, the green section resembles our 5x5x1 input image, I. The element involved in carrying out the convolution operation in the first part of a Convolutional Layer is called the Kernel/Filter, K, represented in the color yellow. We have selected K as a 3x3x1 matrix.

### Padding
In the above demonstration, the blue section is the image on which the convolution operation is applied. We can see the image is expanded by one pixel on all the sides. These extra pixels are called padding.

### Stride
In the demonstration shown above the convolution filter shifts by 2 pixels everytime. So the stride is 2. Stride means the no of pixels it moves everytime.

![](https://i.imgur.com/it160e9.png)

### Pooling

Pooling layer shown in the picture above is used to reduce the dimentionality of image. Pooling layers are of two types max pooling and avg pooling.


## Implementation details

### Netowork defined

Strided convolutional layers were used. Relu activation function was used followed by Maxpooling. Dropout regularization was used to prevent overfitting. Finally a softmax layer was used for prediction.

![](https://i.imgur.com/g7IL6wA.png)


### Results
 Test accuracy of 98% was obtained.
![](https://i.imgur.com/lnXpcHX.png)
