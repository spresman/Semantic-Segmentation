## U-Net Model for Image Segmentation

This repository contains code for training and using a U-Net model for image segmentation. The U-Net architecture is a popular choice for semantic segmentation tasks, such as segmenting objects in an image. It consists of an encoder-decoder structure with skip connections, allowing for better localization of object boundaries.

A U-Net is a common convolutional neural network (CNN) architecture well-suited for image segmentation tasks, specifically developed for biomedical image segmentation. The architecture consists of encoding and decoding blocks, which comprise up and down paths of the U-Net. The encoder extracts important features and propagates them down into lower resolution layers, while the decoder propagates the features to higher resolution layers. This yields a "U" shape, which gives the network its name. Skip connections are utilized between an encoder and its successive decoder to retain spatial information and improve the accuracy of the segmentation.
Project details: A U-Net was built from scratch using the keras, an open-source software library that provides a Python interface for neural networks and deep learning. The data used was obtained from the "Electron Microscopy Dataset" provided by EPFL. The network was trained for 25 epochs and reached a training accuracy of 98.68% and a validation accuracy of 97.67%.

Dataset: https://www.epfl.ch/labs/cvlab/data/data-em/

### Features

- Provides functions for loading and processing images and masks.
- Splits images and masks into quadrants for faster processing.
- Builds the U-Net model.
- Trains the U-Net model with the given data and parameters.
- Plots training and validation accuracy and loss.
- Predicts masks for test images using the trained model.
- Displays test images, ground truth masks, and predicted masks.
- Saves the trained model.


