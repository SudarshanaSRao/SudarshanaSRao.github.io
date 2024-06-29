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
<style>
  .course-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px; /* Adjust as needed for spacing between items */
    width: 100%;
    max-width: 800px;
    margin: 20px auto;
    overflow: hidden;
  }
  .course {
    width: 400px; /* Adjust width as needed */
    margin-bottom: 10px; /* Adjust spacing between items */
    text-align: center; /* Center align text */
  }
  .course img {
    width: 400px;
    height: 400px;
    margin-top: 10px; /* Adjust spacing between image and text */
    opacity: 0;
    transform: translateX(50px); /* Start further left off-screen */
    transition: opacity 0.6s ease-out, transform 0.6s ease-out;
  }
  .course img.show {
    opacity: 1;
    transform: translateX(0); /* Slide to default position */
  }
</style>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    const images = document.querySelectorAll('.course img'); // Select images within courses
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        } else {
          entry.target.classList.remove('show');
        }
      });
    }, {
      threshold: 0.5 // Adjust the threshold to control when the animation triggers
    });
    images.forEach(image => {
      observer.observe(image);
    });
  });
</script>
