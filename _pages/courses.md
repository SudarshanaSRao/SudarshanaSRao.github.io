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

* CSCI 561 Foundations of AI
* EE 541   A Computational Introduction to Deep Learning
* CSCI 585 Database systems
* CSCI 499 Language Models in Natural Language Processing
* EE 559   Machine Learning
* EE 599   Robotic Mobility

Fundamental Courses
==================
* EE 503  Probability for Electrical and Computer Engineers
* EE 510  Linear Algebra for Engineering
* 19EI5PE1PY Python Programming and Applications
* 18CS2ESCCP C & C++ Programming

Online Courses
==================
{% raw %}
<style>
  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
  .fade-in-text {
    opacity: 0; /* Start with opacity 0 */
    color: orange;
    transition: opacity 1.5s ease-out; /* Use transition for fade-in effect */
  }
  .fade-in-text.show {
    opacity: 1; /* Fade to opacity 1 when in view */
  }
  .course-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px; /* Adjust as needed for spacing between items */
  }
  .course {
    width: 400px; /* Adjust width as needed */
    margin-bottom: 10px; /* Adjust spacing between items */
    text-align: center; /* Center align text */
    position: relative; /* Needed for overlay effect */
    overflow: hidden; /* Hide the overflow */
  }
  .course img {
    width: 400px;
    height: 400px;
    margin-top: 5px; /* Adjust spacing between image and text */
    transition: transform 0.5s ease-out; /* Smooth transition for zoom effect */
  }
  .course:hover img {
    transform: scale(1.05); /* Slightly zoom in on hover */
  }
  .course .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background */
    opacity: 0; /* Start with opacity 0 */
    transition: opacity 0.5s ease-out; /* Smooth transition for fade-in effect */
  }
  .course:hover .overlay {
    opacity: 1; /* Fade to opacity 1 on hover */
  }
  .course .overlay .fade-in-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    opacity: 1; /* Ensure text is visible */
  }
</style>
<div class="course-container">
  <div class="course">
    <div class="overlay">
      <p class="text fade-in-text"><i>✦Data Analytics✦</i></p>
    </div>
    <img src="/images/Google Data Analytics.jpg">
  </div>
  <div class="course">
    <div class="overlay">
      <p class="text fade-in-text"><i>✦Microsoft Azure Machine Learning✦</i></p>
    </div>
    <img src="/images/gluck.png">
  </div>
  <div class="course">
    <div class="overlay">
      <p class="text fade-in-text"><i>✦Data Visualization✦</i></p>
    </div>
    <img src="/images/uiuc_cou.png">
  </div>
  <div class="course">
    <div class="overlay">
      <p class="text fade-in-text"><i>✦Using Python to Access Web Data✦</i></p>
    </div>
    <img src="/images/umich_2.png">
  </div>
  <div class="course">
    <div class="overlay">
      <p class="text fade-in-text"><i>✦Python Data Structures✦</i></p>
    </div>
    <img src="/images/umich_3.png">
  </div>
  <div class="course">
    <div class="overlay">
      <p class="text fade-in-text"><i>✦Getting Started with Python✦</i></p>
    </div>
    <img src="/images/umich_1.png">
  </div>
</div>
{% endraw %}
