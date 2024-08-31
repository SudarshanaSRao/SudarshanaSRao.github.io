---
title: "🤏Deep Learning based American Sign Language Recognition"
excerpt: "<img height='500'  width='500' src='/images/preprocess.png'>"
collection: portfolio
---

<img src="/images/test-dataset1.png" style="cursor: crosshair;">
<img src="/images/dataset.png" style="cursor: crosshair;">

* Developed three classes of Artificial Neural Network (ANN) models using the PyTorch framework to translate American Sign Language (Kaggle dataset) into a text-based representation.

<img src="/images/cnnarchitecture.jpg" style="cursor: crosshair;">

* First class was a single generic **Multilayer Perceptron (MLP)** network.
* Second class was two untrained **CNNs (Convolutional Neural Networks)**- a baseline CNN and a custom CNN (with Adam optimizer and L2 regularization).
* Third class was used to leverage **Transfer Learning** with two pre-trained CNNs- **GoogLeNet** and **ResNet18** networks.
* All five models were tested using images captured in real-time and achieved an accuracy of above **90%**.

<img src="/images/googlenet_training.png" style="cursor: crosshair;">

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/EE541-final_project-USC" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>
<style>
@keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
  100% {
    transform: scale(1);
  }
}
.pulse {
  animation: pulse 2s infinite ease-in-out;
}
  </style>
