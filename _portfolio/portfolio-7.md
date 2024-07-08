---
title: "Single cell RNA sequencing"
excerpt: '<br><img src="/images/diagb.png" height="500"  width="500">'
collection: portfolio
---

* Identified important cells among the dataset and ranked in a hierarchy using **k-means clustering** and **Logistic Regression**.  
* The dataset comprised 2169 cells taken from the neocortex region of a rat's brain and distributed in 20,000 columns. **Principal Component Analysis** was used to reduce 20,000 columns to 3-5 components.
* Visualized the output data through a dynamic 3-D graph using **Plotly**.

![clust](/images/3d.gif)
  
* Achieved an accuracy of **89.8%**.

![BD](/images/acc.png)

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/RNA-sequencing" onclick="trackOutboundLink(this);">
      <img class="bounce" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>
<style>
  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% { transform: rotate(0deg); }
    40% { transform: rotate(10deg); }
    60% { transform: rotate(7deg); }  
  }
  .bounce {
    display: inline-block;
    animation: bounce 1.3s ease infinite;
    transform-origin: center; /* Pivot around the top center */
  }
</style>
