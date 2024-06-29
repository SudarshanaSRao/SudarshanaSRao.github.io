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
      <img src="Google Data Analytics.jpg" alt="Data Analytics Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
    <li>Microsoft Azure Machine Learning [Microsoft Learn AI Skills Challenge]
      <img src="gluck.png" alt="Microsoft Azure ML Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
            <li>Data Visualization [University of Illinois at Urbana Champaign, Coursera]
      <img src="uiuc_cou.png" alt="Data Visualization Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
        <li>Using Python to Access Web Data [University of Michigan, Coursera]
      <img src="umich_2.png" alt="Using Python to Access Web Data Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
        <li>Python Data Structures [University of Michigan, Coursera]
      <img src="umich_3.png" alt="Python Data Structures Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
     <li>Programming for Everybody (Getting Started with Python) [University of Michigan, Coursera]
      <img src="umich_1.png" alt="Programming for Everybody Certificate" style="width: 50px; cursor: pointer;" onclick="openModal(this.src);">
    </li>
  </ul>
</div>
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>
{% endraw %}
<style>
.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  padding-top: 100px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgb(0,0,0);
  background-color: rgba(0,0,0,0.9);
}
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
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
function openModal(src) {
  document.getElementById('img01').src = src;
  document.getElementById('myModal').style.display = "block";
}
// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];
// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  document.getElementById('myModal').style.display = "none";
}
</script>
