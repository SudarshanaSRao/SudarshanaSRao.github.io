---
layout: archive
permalink: /courses/
title: "Academic Coursework (Subjects)📚"
excerpt: "Academic courses/subjects"
author_profile: true
redirect_from: 
  - /courses
---
{% include base_path %}
<!-- Graduate Coursework:  -->

⁌ [CSCI 561](https://github.com/SudarshanaSRao/CSCI561-AI_USC){:target="_blank"} Foundations of Artificial Intelligence<br>
⁌ [EE 541](https://github.com/SudarshanaSRao/EE541-Deep_Learning-USC){:target="_blank"}   A Computational Introduction to Deep Learning [✨I was awarded _extra credit_ for the [final project](https://sudarshanasrao.github.io/portfolio/portfolio-5/)✨]<br>
⁌ [CSCI 585](https://github.com/SudarshanaSRao/USC_CSCI-585_Database-Systems){:target="_blank"} Database systems [🚀I was the Course Producer during _Spring '24_ term🚀]<br>
⁌ [CSCI 499](https://github.com/SudarshanaSRao/CSCI-499_LMs-in-NLP_USC){:target="_blank"} Language Models in Natural Language Processing<br>
⁌ [EE 559](https://github.com/SudarshanaSRao/EE559-Machine_Learning-USC){:target="_blank"}   Machine Learning<br>
⁌ [EE 599](https://github.com/SudarshanaSRao/USC_EE-599_Robotics){:target="_blank"}   Robotic Mobility [🥈My team’s [final project](https://www.youtube.com/watch?v=7GFFjOJgJMA){:target="_blank"} earned _second place_ in the cohort🥈]<br>

Fundamental Courses
==================
⁌ EE 503  Probability for Electrical and Computer Engineers<br>
⁌ EE 510  Linear Algebra for Engineering<br>
⁌ [19EI5PE1PY](https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML){:target="_blank"} Python Programming and Applications (Data Structures and Algorithms)<br>
⁌ 18CS2ESCCP C & C++ Programming

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
    font-weight: normal;
    color: orange;
    transition: opacity 1.5s ease-out; /* Use transition for fade-in effect */
  }
  .fade-in-text.show {
    opacity: 1; /* Fade to opacity 1 when in view */
  }
  .course-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px; /* Adjust as needed for spacing between items */
    justify-content: center; /* Center align all items */
  }
  .course {
    flex: 0 1 calc(50% - 20px); /* Ensure two items per row with spacing */
    box-sizing: border-box; /* Include padding and border in the element's total width and height */
    margin-bottom: 20px; /* Adjust spacing between rows */
    text-align: center; /* Center align text */
    position: relative; /* Needed for overlay effect */
    overflow: hidden; /* Hide the overflow */
  }
  .course img {
    width: 100%; /* Ensure the image fits the container */
    height: auto; /* Maintain aspect ratio */
    transition: transform 0.5s ease-out; /* Smooth transition for zoom effect */
    cursor: zoom-in; /* Change cursor to magnifying glass */
  }
  .course:hover img {
    transform: scale(1.1); /* Slightly zoom in on hover */
  }
  .course .fade-in-text {
    margin-top: 10px; /* Space between text and image */
  }
</style>
<div class="course-container">
  <div class="course">
    <p class="text fade-in-text"><i>➤ Data Analytics</i></p>
    <img src="/images/Google Data Analytics.jpg">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ Microsoft Azure Machine Learning</i></p>
    <img src="/images/gluck.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ Data Visualization</i></p>
    <img src="/images/uiuc_cou.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ Using Python to Access Web Data</i></p>
    <img src="/images/umich_2.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ Python Data Structures</i></p>
    <img src="/images/umich_3.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ Getting Started with Python</i></p>
    <img src="/images/umich_1.png">
  </div>
    <div class="course">
    <p class="text fade-in-text"><i>➤ ML/DL Workshop</i></p>
    <img src="/images/ML DL workshop.png">
  </div>
      <div class="course">
    <p class="text fade-in-text"><i>➤ IIT-Bombay Python</i></p>
    <img src="/images/IITB python course.jpg">
  </div>
        <div class="course">
    <p class="text fade-in-text"><i>➤ Robotic Process Automation</i></p>
    <img src="/images/LearningPath_Certificate_07232021141549826.jpg">
  </div>
          <div class="course">
    <p class="text fade-in-text"><i>➤ Smart Room with Alexa</i></p>
    <img src="/images/Smart room with alexa.jpg">
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
