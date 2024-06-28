---
layout: archive
title: "Adventurous Me!🤸‍♂️"
permalink: /personal/
author_profile: true
redirect_from:
  - /personal
---

{% include base_path %}

I enjoy traveling ✈️, hiking 🥾, playing cricket 🏏, reading the news 🗞️, and watching movies 🍿 & TV shows 📽️ in my free time. Hit me up if you want to play video games 🎮 with me!  

Scroll down 🖱️⬇️ to see cool pictures 😎 of me around the world:

<div class="container">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.02_180d4cf9.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_2896198e.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.02_bf5bccb7.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_cd38722a.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_5ea38d29.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_21151693.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_9976057a.jpg" class="image">
  <img src="/images/grouppic.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_8d775df7.jpg" class="image">
</div>
<style>
/*   body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
  } */
  .container {
    width: 100%;
    max-width: 800px;
    margin: 20px auto;
    overflow: hidden;
  }
  .image {
    width: 100%;
    height: 100%;
    margin: 20px 0;
    opacity: 0;
    transform: translateX(-50px);
    transition: opacity 0.6s ease-out, transform 0.6s ease-out;
  }
  .image.show {
    opacity: 1;
    transform: translateX(0);
  }
</style>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    const images = document.querySelectorAll('.image');
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        } else {
          entry.target.classList.remove('show');
        }
      });
    }, { threshold: 0.5 });  // Adjust as needed to control when animation starts
    images.forEach(image => {
      observer.observe(image);
    });
  });
</script>
