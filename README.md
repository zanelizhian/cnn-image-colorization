CNN for Image Colorization (Python, Keras, Machine Learning Class Project)

- Created a convolutional neural network to convert greyscale bird images from CIFAR-10 to four-color images (color selected using k-means clustering from the training set). Trained for 30 Epoch and reached training accuracy 0.69, test accuracy 0.58.

- Network contains three convolutional layers and three dense layers. Also used SoftMax and pooling technique. 

- Took the project beyond class level, expanded the neural network and colorized images using 8, 16, and 32 different colors. 



The file named Keras.ipynb contains the main part of the project.

The file named Keras16/24/32 contains code when k is larger. I didn't change the convolution layers of the network, but slightly altered the number of neurons in the dense layer.

The file named ResNet tried to use Internet code on ResNet34 to solve the problem