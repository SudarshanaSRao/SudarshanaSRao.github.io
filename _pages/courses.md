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

### Fundamentals
* EE 503  Probability for Electrical and Computer Engineers
* EE 510  Linear Algebra for Engineering
* 19EI5PE1PY Python Programming and Applications
* 18CS2ESCCP C & C++ Programming

### Online courses
{% raw %}
<div class="course-list">
  <ul>
    <li>Data Analytics [Google, Coursera]
      <img src="/images/Google Data Analytics.jpg" alt="Data Analytics Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
    <li>Microsoft Azure Machine Learning [Microsoft Learn AI Skills Challenge]
      <img src="/images/gluck.png" alt="Microsoft Azure ML Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
            <li>Data Visualization [University of Illinois at Urbana Champaign, Coursera]
      <img src="/images/uiuc_cou.png" alt="Data Visualization Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
        <li>Using Python to Access Web Data [University of Michigan, Coursera]
      <img src="/images/umich_2.png" alt="Using Python to Access Web Data Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
        <li>Python Data Structures [University of Michigan, Coursera]
      <img src="/images/umich_3.png" alt="Python Data Structures Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
     <li>Programming for Everybody (Getting Started with Python) [University of Michigan, Coursera]
      <img src="/images/umich_1.png" alt="Programming for Everybody Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
  </ul>
</div>
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>
{% endraw %}
<style>
.modal {
  display: none; /* Ensures modal is hidden on page load */
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0,0,0,0.8); /* Dim the background */
  z-index: 1000; /* Ensures modal is on top of other content */
  padding: 20px;
  align-items: center;
  justify-content: center;
  flex-direction: column; /* Stacks items vertically */
}
.modal-content {
  display: block;
  max-width: 80%; /* Responsive max width, consider adjusting this */
  max-height: 80vh; /* Responsive max height, consider adjusting this */
  width: auto; /* Maintain aspect ratio */
  height: auto; /* Adjust based on your needs */
  margin: auto; /* Centering the image within the modal */
}
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}
.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}
</style>
<script>
document.addEventListener('DOMContentLoaded', function () {
  var modal = document.getElementById('myModal');
  var modalImg = document.getElementById('img01');
  var span = document.getElementsByClassName("close")[0]; // Close button
  window.openModal = function(src) {
    var modalImg = document.getElementById('img01');
    modalImg.src = src;
    modal.style.display = "flex"; // Show the modal
  }
  span.onclick = function() {
    modal.style.display = "none";
  }
  window.onclick = function(event) {
    if (event.target == modal) {
      modal.style.display = "none";
    }
  }
});
</script>
