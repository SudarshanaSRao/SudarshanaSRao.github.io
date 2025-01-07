---
layout: archive
permalink: /courses/
title: "Academic Coursework (Subjects)📚"
excerpt: "Academic & online courses/subjects"
author_profile: true
redirect_from: 
  - /courses
---
{% include base_path %}

<style>
/* Container for Bullet List */
.bullet-list {
  list-style-type: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
}
/* Bullet List Item */
.bullet-list li {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
  width: 100%;  /* Ensures the list items take up the full width */
}
/* Custom Bullet */
.bullet-list li::before {
  content: "⁌";  /* Custom bullet symbol */
  font-size: 20px;
  margin-right: 10px;
}
/* Text next to the button */
.text-right {
  font-size: 18px;
  flex-grow: 1;  /* Makes the text take up the remaining space */
  text-align: left;  /* Aligns text to the left */
}
/* Button Styles */
.download-paper-button {
  border: 2px solid #000;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-flex;
  align-items: center;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 4px;
  background-color: transparent;
  color: black;
  font-weight: bold;
  transition: background-color 0.3s ease-in-out, border-color 0.3s ease-in-out;
}
.download-paper-button::before {
  content: "";
  background-image: url("/images/A.jpg");  /* Specify the path to the image */
  background-size: contain;  /* Adjust size of the image */
  background-repeat: no-repeat;  /* Prevent repetition of the image */
  width: 20px;  /* Adjust width */
  height: 20px;  /* Adjust height */
  margin-right: 8px;  /* Space between image and text */
  display: inline-block;  /* Makes it an inline element */
}
/* Hover Effect */
.download-paper-button:hover {
  background-color: #A9A9A9;
  color: white;
  border-color: #696969;
  transform: translateY(-3px);
}
/* Active Effect */
.download-paper-button:active {
  background-color: #696969;
  border-color: #696969;
  transform: translateY(2px);
  box-shadow: 0 2px #D3D3D3;
}
/* Responsive Styles */
@media (max-width: 600px) {
  /* Adjust button text size and margins for smaller screens */
  .download-paper-button {
    font-size: 14px;
    padding: 8px 16px;
  }
  .text-right {
    font-size: 16px;
  }
}
</style>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/CSCI561-AI_USC" target="_blank">
        <button class="download-paper-button">
          CSCI 561
        </button>
      </a>
      <span class="text-right">Foundations of Artificial Intelligence</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/CSCI-499_LMs-in-NLP_USC" target="_blank">
        <button class="download-paper-button">
          CSCI 499
        </button>
      </a>
      <span class="text-right">Language Models in Natural Language Processing</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/USC_CSCI-585_Database-Systems" target="_blank">
        <button class="download-paper-button">
          CSCI 585
        </button>
      </a>
      <span class="text-right">Database systems [🚀I was the Course Producer during <i>Spring '24</i> term🚀]</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/EE541-Deep_Learning-USC" target="_blank">
        <button class="download-paper-button">
          EE 541
        </button>
      </a>
      <span class="text-right">A Computational Introduction to Deep Learning [✨I was awarded <i>extra credit</i> for the <a href="https://sudarshanasrao.github.io/portfolio/portfolio-5/">final project</a>✨]</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/EE559-Machine_Learning-USC" target="_blank">
        <button class="download-paper-button">
          EE 559
        </button>
      </a>
      <span class="text-right">Machine Learning</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/USC_EE-599_Robotics" target="_blank">
        <button class="download-paper-button">
          EE 599
        </button>
      </a>
      <span class="text-right">Robotic Mobility [🥈My team’s <a href="https://www.youtube.com/watch?v=7GFFjOJgJMA" target="_blank">final project</a> earned <i>second place</i> in the cohort🥈]</span>
    </li>
  </ul>
</div>   

Fundamental Courses
==================
<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <a href="https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML" target="_blank">
        <button class="download-paper-button">
          19EI5PE1PY
        </button>
      </a>
      <span class="text-right">Python Programming and Applications (Data Structures and Algorithms)</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <span class="text-right">18CS2ESCCP C & C++ Programming</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <span class="text-right">EE 503 Probability for Electrical and Computer Engineers</span>
    </li>
  </ul>
</div>

<div class="download-button-container">
  <ul class="bullet-list">
    <li>
      <span class="text-right">EE 510 Linear Algebra for Engineering</span>
    </li>
  </ul>
</div>

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
    .fade-in-text a {
    color: orange; /* Ensure the link text is orange */
    text-decoration: underline; /* Add underline for the link */
    font-weight: normal; /* Maintain normal font weight */
  }
  .fade-in-text a:hover {
    color: orange; /* Keep the color orange on hover */
    text-decoration: underline; /* Keep underline on hover */
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
    <p class="text fade-in-text"><i>➤ <a href="https://www.coursera.org/account/accomplishments/verify/CLMTY5DJJA7K" target="_blank">Data Visualization</a></i></p>
    <img src="/images/uiuc_cou.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ <a href="https://www.coursera.org/account/accomplishments/verify/QLKEY6H5LLAA" target="_blank">Using Python to Access Web Data</a></i></p>
    <img src="/images/umich_2.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ <a href="https://www.coursera.org/account/accomplishments/verify/TSENVHDS4NZF" target="_blank">Python Data Structures</a></i></p>
    <img src="/images/umich_3.png">
  </div>
  <div class="course">
    <p class="text fade-in-text"><i>➤ <a href="https://www.coursera.org/account/accomplishments/verify/GJEDU3PKFP5J" target="_blank">Getting Started with Python</a></i></p>
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
