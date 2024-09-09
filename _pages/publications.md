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
    text-decoration: none;
  } 
  .dropdown-content {
    display: block;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 200px;
    overflow: hidden;
    overflow-y: auto; /* Enable scrolling */
    box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
    border-radius: 4px;
    top: 100%; /* Positions the dropdown below the button */
    right: 0;
    transition: max-height 0.3s ease-in-out, opacity 0.3s ease-in-out, transform 0.3s ease-in-out; /* Ensure scaling happens from the left */
    max-height: 0;
    opacity: 0;
    transform: scaleY(0);
    transform-origin: top;
  }
  .dropdown-content.show {
    max-height: 400px; /* Fully expanded state */
    opacity: 1;
    transform: scaleY(1);
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
    text-decoration: none;
  }
 .dropdown-content::-webkit-scrollbar {
    width: 12px; /* Width of the scrollbar */
  }
  .dropdown-content::-webkit-scrollbar-track {
    background: rgba(0, 0, 0, 0.1); /* Background of the scrollbar track */
    border-radius: 6px; /* Rounded corners */
  }
  .dropdown-content::-webkit-scrollbar-thumb {
    background-color: #777; /* Scrollbar color */
    border-radius: 6px; /* Rounded corners */
    border: 3px solid rgba(0, 0, 0, 0); /* Space around the scrollbar */
    background-clip: padding-box; /* Prevent border from overlapping scrollbar */
  }
  .dropdown-content::-webkit-scrollbar-thumb:hover {
    background-color: #666; /* Scrollbar color on hover */
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
.project-separator {
  width: 90%;
  margin: 20px auto;
  position: relative;  /* Allows positioning of the pseudo-element */
  height: 3px;  /* Height of the separator */
  background: #ddd;  /* Fallback color */
}
.project-separator::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 100%;  
  /* Multicolor gradient applied to the separator */
  background: linear-gradient(135deg, #ff7078 0%, #f8a1b0 25%, #f58ad4 50%, #8b70c1 75%, #f8a1b0 100%);
}
</style>

<nav class="navbar">
  <ul class="navbar-list">
    <li class="navbar-item dropdown" onmouseover="showDropdown()" onmouseout="hideDropdown()" onclick="toggleDropdown()">
      <a href="javascript:void(0)" class="dropbtn">
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
    <hr> <!-- Horizontal line added here -->
</div>
{% endfor %}

<script>
  function showDropdown() {
    var dropdownContent = document.querySelector('.dropdown-content');
    var dropdownArrow = document.getElementById('dropdown-arrow');
    dropdownContent.classList.add('show');
    dropdownArrow.innerHTML = "▲";
  }
  function hideDropdown() {
    var dropdownContent = document.querySelector('.dropdown-content');
    var dropdownArrow = document.getElementById('dropdown-arrow');
    dropdownContent.classList.remove('show');
    dropdownArrow.innerHTML = "▼";
  }
  function toggleDropdown() {
    var dropdownContent = document.querySelector('.dropdown-content');
    var dropdownArrow = document.getElementById('dropdown-arrow');
    if (dropdownContent.classList.contains('show')) {
      hideDropdown();
    } else {
      showDropdown();
    }
  }
</script>
