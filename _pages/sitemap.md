---
layout: archive
title: "Sitemap🌐"
excerpt: "Web layout of my website"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the web pages found on this site. For you robots out there, here's an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

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
