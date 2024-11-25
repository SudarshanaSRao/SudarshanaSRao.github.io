---
title: "🧬Single cell RNA sequencing"
excerpt: '<br><img src="/images/diagb.png" height="500"  width="500" style="cursor: crosshair;">'
collection: portfolio
tags: 
  - Python
  - Machine Learning models
  - Plotly
  - 3-D graphs
---

* Identified important cells among the dataset and ranked in a hierarchy using **k-means clustering** and **Logistic Regression**.  
* The dataset comprised _2169 cells_ taken from the neocortex region of a rat's brain and distributed in _20,000 columns_. **Principal Component Analysis** was used to _reduce 20,000 columns to 3-5 components_.
* Visualized the output data through a dynamic 3-D graph using **Plotly**.

<img src="/images/3d.gif" style="cursor: crosshair;">
  
* Achieved an accuracy of **89.8%**.

<img src="/images/acc.png" style="cursor: crosshair;">

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/RNA-sequencing" target="_blank" onclick="trackOutboundLink(this);">
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
