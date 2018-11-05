# Learning_Tensorflow
This repository will contain basic Tensorflow tutorials and deep learning concepts. It'll also contain some experiments on some papers that I read and some interesting model that I find on Internet or books. Hopefully, the repository will be helpful to everyone reading!   

**[Basic](https://github.com/Quan-Sun/Learning_Tensorflow/tree/master/Basic)** - a file contains basic Tensorflow tutorials, such as graph, session, tensor, nerual networks, CNN, etc. 

**[CNNs with Noisy Labels](https://github.com/Quan-Sun/Learning_Tensorflow/blob/master/CNNs%20with%20Nosiy%20Labels.ipynb)** - a notebook for an interesting experiment that I found on Github, which tests how convolutional neural networks that are trained on random labels (with some probability) are still able to acheive good accuracy on MNIST. However, my result shows a different conclusion that the random labels can surely affect the CNNs' performance.

**[CIFAR10](https://github.com/Quan-Sun/Learning_Tensorflow/tree/master/CIFAR10)** - a file contaions models for CIFAR-10 classification. CIFAR-10 classification is a common benchmark problem in machine learning. The problem is to classify RGB 32x32 pixel images across 10 categories:airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck.The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

**[Universal Approximation Theorem](https://github.com/Quan-Sun/Learning_Tensorflow/blob/master/Universal%20Approximation%20Theorem.ipynb)** - The Universal Approximation Theorem states that any feed forward neural network with a single hidden layer containing a finite number of neurons can fit any function. This notebook Creates a neural networks with one hidden layer to classifies all samples in MNIST. I respectively set 20 and 1000 hidden neurons, and test the performance of models.
