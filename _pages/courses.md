---
layout: archive
permalink: /courses/
title: "Graduate Coursework📚"
excerpt: "Courses📚"
author_profile: true
redirect_from: 
  - /courses
---
{% include base_path %}
<!-- Graduate Coursework:  -->

* EE 541   A Computational Introduction to Deep Learning
* CSCI 585 Database systems
* CSCI 499 Language Models in Natural Language Processing
* EE 559   Machine Learning
* CSCI 561 Foundations of AI

## Fundamentals
* EE 503  Probability for Electrical and Computer Engineers
* EE 510  Linear Algebra for Engineering
* 19EI5PE1PY Python Programming and Applications
* 18CS2ESCCP C & C++ Programming

## Online courses
{% raw %}
<style>
  .course-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px; /* Adjust as needed for spacing between items */
  }
  .course {
    width: 400px; /* Adjust width as needed */
    margin-bottom: 10px; /* Adjust spacing between items */
    text-align: center; /* Center align text */
    overflow: hidden; /* Hide parts of the image that slide in */
  }
  .course img {
    width: 400px;
    height: 400px;
    margin-top: 10px; /* Adjust spacing between image and text */
    transition: transform 0.5s ease-in-out; /* Smooth transformation for sliding */
  }
</style>
<script>
document.addEventListener("scroll", function() {
  var scrollPosition = window.pageYOffset; // Get current scroll position
  var images = document.querySelectorAll('.course img'); // Select all course images
  images.forEach(function(img, index) {
    var deltaX = scrollPosition * (0.1 + index * 0.05); // Calculate horizontal shift
    img.style.transform = 'translateX(' + deltaX + 'px)'; // Apply horizontal shift
  });
});
</script>
<div class="course-container">
  <div class="course">
    <p><strong>Data Analytics</strong></p>
    <img src="/images/Google Data Analytics.jpg">
  </div>
  <div class="course">
    <p><strong>Microsoft Azure Machine Learning</strong></p>
    <img src="/images/gluck.png">
  </div>
  <div class="course">
    <p><strong>Data Visualization</strong></p>
    <img src="/images/uiuc_cou.png">
  </div>
  <div class="course">
    <p><strong>Using Python to Access Web Data</strong></p>
    <img src="/images/umich_2.png">
  </div>
  <div class="course">
    <p><strong>Python Data Structures</strong></p>
    <img src="/images/umich_3.png">
  </div>
  <div class="course">
    <p><strong>Getting Started with Python</strong></p>
    <img src="/images/umich_1.png">
  </div>
</div>
{% endraw %}
