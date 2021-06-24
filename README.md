# Image Classifiers

The following repository consists of two different types of image classifiers. The first one being a basic artificial neural network while the other network is designed using transfer learning.

## Libraries Used

The predominantly used python libraries are Numpy and Pytorch.

## Dataset

A customised dataset of 1600 images was used for the classifiers. The imageset consisted of 800 images of educational notes and 800 images of recreational memes. The images are divided into train and test set. 760 images from each class are taken for training set while the remaining 40 images from each class are used in the test set.

* **Train Set:** <br> 
Total Images: 1520 <br>
Memes Class : 760  <br>
Notes Class : 760

* **Test Set:** <br> 
Total Images: 80 <br>
Memes Class : 40 <br>
Notes Class : 40

## Classifier 1: Artificial Neural Network Image Classifier

The classifier consists of a 4 hidden layered neural network. Each hidden layered is activated using the RELU activation function while the output function is activated using the Sigmoid activation function.

## Classifier 2: Transfer Learning Image Classifier

The classifier uses the concept of transfer learning using a pretrained Resnet 50 model.