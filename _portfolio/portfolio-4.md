---
title: "ML Based Traffic Light Detection and IR Sensor Based Proximity Sensing for Autonomous Cars"
excerpt: '<br><img src="/images/mlblock.png" height="500"  width="500">'
collection: portfolio
---

* Used **OpenCV2** library to build an automated system to detect and recognize traffic lights for an autonomous car.
* **Hough Gradient Descent** was used to train the model, and **Hough Circles** were drawn around the detected traffic light.
* **IR sensor** (interfaced with an **Arduino Uno board**) was used to monitor the distance between the autonomous car and nearby obstacles or traffic.
* The system was live-tested on the streets of Bangalore, and excellent results were achieved.

![block](/images/outputml.png)

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/Traffic-light-detection-and-recognition" onclick="trackOutboundLink(this);">
      <img class="bounce" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>
    
<div class="flexcontainer">
  <div>
        <span>✦ <strong>Publication:</strong></span> <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3883931" onclick="trackOutboundLink(this);">
      <img class="bounce" height="70px" src="/images/download_SSRN.jpg" width="150px">
    </a>
  </div>
</div>
<style>
  .flexcontainer {
    display: flex;
    align-items: center;
    margin-bottom: 20px; /* Adjust the value as needed */
    }
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

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
