---
layout: archive
title: 
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}
<style>
  .navbar {
    background-color: #666;
    position: fixed;
    top: 90px; /* Adjust this value to control the vertical position */
    right: 75px; /* Adjust this value to control the horizontal position */
    width: 260px; /* Adjust width as needed */
    border-radius: 8px;
    box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
    z-index: 1000; /* Ensures it floats above other content */
  }
  .navbar-list {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  .navbar-item {
    position: relative;
  }
  .navbar-item a, .dropbtn {
    display: block;
    color: white;
    text-align: center;
    padding: 10px;
    text-decoration: none;
    border-bottom: 1px solid #666; /* Adds separation between menu items */
  }
  .navbar-item a:hover, .dropdown:hover .dropbtn {
    background-color: #555;
  } 
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 200px;
    max-height: 400px; /* Limit height to 400px */
    overflow-y: auto; /* Enable scrolling */
    box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
    border-radius: 4px;
    top: 100%; /* Positions the dropdown below the button */
    right: 0;
    z-index: 1000;
  }
  .dropdown-content a {
    color: black;
    padding: 10px;
    text-decoration: none;
    display: block;
    text-align: left;
    border-bottom: 1px solid #ddd; /* Adds separation between dropdown items */
  }
  .dropdown-content a:hover {
    background-color: #f1f1f1;
  }
  .dropdown:hover .dropdown-content,
  .dropbtn:focus + .dropdown-content,
  .dropdown-content:hover {
    display: block;
  }
  @media screen and (max-width: 768px) {
    .navbar {
      top: 50px; /* Adjust position for smaller screens */
      right: 20px; /* Adjust position for smaller screens */
      width: 160px; /* Adjust width for smaller screens */
    }
    .dropdown-content {
      min-width: 140px; /* Adjust dropdown width for smaller screens */
      max-height: 200px; /* Adjust dropdown height for smaller screens */
    }
  }
</style>

<nav class="navbar">
  <ul class="navbar-list">
    <li class="navbar-item dropdown">
      <a href="javascript:void(0)" class="dropbtn" onclick="toggleDropdown()">
        <span id="dropdown-arrow" style="margin-right: 30px;">▼</span>
        <span style="font-size: 24px; font-weight: bold;">Publications📜</span>
      </a>
      <div class="dropdown-content">
        {% for post in site.publications %}
          <a href="#{{ post.title | slugify }}">{{ post.title }}</a>
        {% endfor %}
      </div>
    </li>
  </ul>
</nav>

{% for post in site.publications %}
<div id="{{ post.title | slugify }}">
    {% include archive-single.html %}
</div>
{% endfor %}

<script>
  function toggleDropdown() {
    var dropdownContent = document.querySelector('.dropdown-content');
    var dropdownArrow = document.getElementById('dropdown-arrow');
    if (dropdownContent.style.display === "block") {
      dropdownContent.style.display = "none";
      dropdownArrow.innerHTML = "▼";
    } else {
      dropdownContent.style.display = "block";
      dropdownArrow.innerHTML = "▲";
    }
  }
</script>
