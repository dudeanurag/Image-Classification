# Image Classification

## Overview
This project is part of the Udacity Deep Learning Foundations Nanodegree. It uses Covolutional Neural Networks to classify images in CIFAR-10 dataset.
The dataset consists of airplanes, dogs, cats, and other objects. We will preprocess the images, then train a convolutional neural network on all the samples. 
The images need to be normalized and the labels need to be one-hot encoded. We will get to apply what you learned and build a convolutional, max pooling, dropout, and fully connected layers. 
At the end, we will get to see your neural network's predictions on the sample images.

## Tools Used
1. Python
2. Tensorflow

## Dataset
CIFAR-10 dataset. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. 
There are 50000 training images and 10000 test images. The dataset is divided into five training batches and one test batch, each with 10000 images. 
The test batch contains exactly 1000 randomly-selected images from each class. 
The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. 
Between them, the training batches contain exactly 5000 images from each class. 

Here are the classes in the dataset, as well as 10 random images from each:
1. airplane										
2. automobile										
3. bird										
4. cat										
5. deer										
6. dog										
7. frog										
8. horse										
9. ship										
10. truck
