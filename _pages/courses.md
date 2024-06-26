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
    transition: opacity 1.3s ease-out; /* Use transition for fade-in effect */
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
  }
  .course img {
    width: 400px;
    height: 400px;
    margin-top: 5px; /* Adjust spacing between image and text */
  }
</style>
<div class="course-container">
  <div class="course">
    <p class="text fade-in-text"><i>✦Data Analytics✦</i></p>
    <img src="/images/Google Data Analytics.jpg">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>✦Microsoft Azure Machine Learning✦</i></p>
    <img src="/images/gluck.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>✦Data Visualization✦</i></p>
    <img src="/images/uiuc_cou.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>✦Using Python to Access Web Data✦</i></p>
    <img src="/images/umich_2.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>✦Python Data Structures✦</i></p>
    <img src="/images/umich_3.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>✦Getting Started with Python✦</i></p>
    <img src="/images/umich_1.png">
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    const textElements = document.querySelectorAll('.fade-in-text');
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        } else {
          entry.target.classList.remove('show');
        }
      });
    });
    textElements.forEach(element => {
      observer.observe(element);
    });
  });
</script>
{% endraw %}
