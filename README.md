# Deep-Learning-for-Image-Classification

## TLDR
* Capstone project for SI 670: Machine Learning
* Data from kaggle dataset: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

## Overview
This notebook uses deep learning approaches to try and diagnose chest x-rays as either healthy or as having pneumonia. More specifically, I compare two transfer learning strategies by utilizing the pre-trained weights from the VGG-16 Convolutional Neural Network (CNN) trained on ImageNet. CNNs have proven to be state-of-art deep learning approaches for computer vision tasks. They perform quite well at identifying key representations from image data. 

The first approach freezes all of the pre-trained weights and layers, and simply adds several dense layers to be trained on the chest x-ray data. The second approach unfreezes a few of the top layers of VGG-16 for training on the medical data. 

## Some results
The notebook file contains more details on the findings and results from each models' performance. Overall, the CNNs perform quite well and outpeform baseline models (dummy classifier & logistic regression). Additionally, the CNNs also learn accurate representations of pneumonia.
