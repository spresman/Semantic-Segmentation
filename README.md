# Semantic-Segmentation

Introduction:
Cellular segmentation consists of separating identified individual cells in an image. This allows researches to study various properties of cells including size, shape, and distribution. 

A U-Net is a common convolutional neural network (CNN) architecture well-suited for image segmentation tasks, specifically developed for biomedical image segmentation. The architecture consists of encoding and decoding blocks, which comprise up and down paths of the U-Net. The encoder extracts important features and propogates them down into lower resolution layers, while the decoder propogates the features to higher resolution layers. This yields a "U" shape, which gives the network its name. Skip connections are utilized between an encoder and its successive decoder to retain spatial information and improve the accuracy of the segmentation. 


Project details:
A U-Net was built from scratch using the keras, an open-source software library that provides a Python interface for neural networks and deep learning. The data used was obtained from the "Electron Microscopy Dataset" provided by EPFL. The network was trained for 25 epochs and reached a training accuracy of 98.68% and a validation accuracy of 97.67%. 

Dataset: https://www.epfl.ch/labs/cvlab/data/data-em/
