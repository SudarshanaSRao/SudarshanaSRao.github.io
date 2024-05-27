---
title: "Deep Learning based American Sign Language Recognition"
excerpt: "<img height='300'  width='300' src='/images/preprocess.png'>"
collection: portfolio
---

![pre](/images/test-dataset1.png)
![dat](/images/dataset.png)

* Developed three classes of Artificial Neural Network (ANN) models using the PyTorch framework to translate American Sign Language (Kaggle dataset) into a text-based representation.

![arch](/images/cnnarchitecture.jpg)

* First class was a single generic **Multilayer Perceptron (MLP)** network.
* Second class was two untrained **CNNs (Convolutional Neural Networks)**- a baseline CNN and a custom CNN (with Adam optimizer and L2 regularization).
* Third class was used to leverage **Transfer Learning** with two pre-trained CNNs- **GoogLeNet** and **ResNet18** networks.
* All five models were tested using images captured in real-time and achieved an accuracy of above **90%**.

![google](/images/googlenet_training.png)

#### ✦ [Code](https://github.com/SudarshanaSRao/EE541-final_project-USC) ✦ 
