# Deep-Learning-for-Image-Classification

## TLDR
* Capstone project for SI 670: Machine Learning
* Data from kaggle dataset: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

This notebook uses deep learning approaches to try and diagnose chest x-rays as either healthy or as having pneumonia. More specifically, I compare two transfer learning strategies by utilizing the pre-trained weights from the VGG-16 neural architecture trained on ImageNet. The first approach freezes all of the pre-trained weights and layers, and simply adds several dense layers to be trained on the chest x-ray data. The second approach unfreezes a few of the top layers of VGG-16 for training on the medical data. 

