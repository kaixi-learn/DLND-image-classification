
# DLND-image-classification
## Introduction

In this project, we classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects.

CIFAR-10  is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class

![alt text](https://kaggle2.blob.core.windows.net/competitions/kaggle/3649/media/cifar-10.png "Logo Title Text 1")


We preprocess the images, then train a convolutional neural network on all the samples. Firstly, the images are normalized and the labels are one-hot encoded. Then we build convolutional layers, pooling layers, dropout operations, and fully connected layers. At the end, we use the convnet to make predictions on the sample images.


## Prerequisite (OSX/Linux)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Anaconda 3](https://www.continuum.io/)
* [Tensorflow](https://www.tensorflow.org/)

## Instruction

    conda create -n tensorflow python=3.5
    source activate tensorflow
    conda install pandas matplotlib jupyter notebook scipy scikit-learn
    pip install tensorflow
