# Apple Orchard Segmentation and Counting

This project aims to segment and count the number of apples in an orchard using U-net segmentation neural network. The code is written in Python and uses the Keras and TensorFlow libraries.

## Overview

The U-net segmentation neural network is used to segment the apples from the background in the orchard images. The segmented images are then processed using traditional computer vision techniques to count the number of apples in each image.

## Dataset

The dataset of images with apple orchards should be prepared such that each image has the apples marked with masks.

## Usage
1. To use the segmentation and counting code, follow these steps:

2. Prepare the dataset of images with apple orchards. Each image should have the apples marked with masks.

3. Split the dataset into training and testing sets.To train the program on a new dataset, change the train and test path in the jupyter file.

4. Train the U-net segmentation neural network using the training set. The model will learn to segment the apples from the background.

5. Test the segmentation model using the testing set. The model will output the segmented apples.

6. Use traditional computer vision techniques to count the number of segmented apples in each image.
