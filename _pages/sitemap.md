---
layout: archive
title: "Sitemap🌐"
excerpt: "Web layout of my website"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the web pages found on this site. For you robots out there, here's an XML version available for digesting as well:

<style>
/* Button Styles */
.download-button {
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
/* Hover Effect */
.download-button:hover {
  background-color: #A9A9A9;
  color: white;
  border-color: #696969;
  transform: translateY(-3px);
}
/* Active Effect */
.download-button:active {
  background-color: #696969;
  border-color: #696969;
  transform: translateY(2px);
  box-shadow: 0 2px #D3D3D3;
}
/* Responsive Styles */
@media (max-width: 600px) {
  /* Adjust button text size and margins for smaller screens */
  .download-button {
    font-size: 14px;
    padding: 8px 16px;
  }
}
</style>

<div class="download-button-container">
      <a href="{{ base_path }}/sitemap.xml">
        <button class="download-button">
          XML version
        </button>
      </a>
</div>

<img src='/images/sitemax.jpg' style="border-radius: 8px; cursor: crosshair;">

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h2>{{ label }}</h2>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}
{% for post in collection.docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single.html %}
  {% endunless %}
{% endfor %}
{% endfor %}
