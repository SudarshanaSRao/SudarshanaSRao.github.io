---
title: "Deep Learning based American Sign Language Recognition"
excerpt: "<img height='500'  width='500' src='/images/preprocess.png'>"
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

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/EE541-final_project-USC" onclick="trackOutboundLink(this);">
      <img class="bounce" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>
<style>
  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% { transform: rotate(0deg); }
    40% { transform: rotate(-10deg); }
    60% { transform: rotate(-7deg); }  
  }
  .bounce {
    display: inline-block;
    animation: bounce 1.3s ease infinite;
    transform-origin: center; /* Pivot around the top center */
  }
  </style>
