---
layout: archive
title: "Adventurous Me!🤸‍♂️"
excerpt: "A sneak peek into my personal life"
permalink: /personal/
author_profile: true
redirect_from:
  - /personal
---

{% include base_path %}

I enjoy ✈️ traveling, 🥾 hiking, 🏏 playing cricket (sports), 🗞️ reading the news, 📟 keeping up with technology, and 🍿 watching movies 📽️ & 📺 TV shows in my free time. Hit me up if you want to 🎮 play video games <img src="https://cdn3.emoji.gg/emojis/3139_Xbox.png" width="15px" height="15px" alt="Xbox"> with me!  

Scroll down 🖱️⬇️ to see cool pictures 😎 of me around the world 🌎: 

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<style>
.cursor {
  display: inline-block;
  animation: blink 0.7s infinite;
  position: relative;
}
@keyframes blink {
  0%, 100% {
    opacity: 1;
  }
  50% {
    opacity: 0;
  }
}
</style>
<span id="typed-text"></span><span class="cursor">_</span>
<div class="social-links mt-3 text-center" style="font-size: xx-large"></div>
<script>
document.addEventListener("DOMContentLoaded", function() {
  var typed = new Typed('#typed-text', {
    strings: ["(Psst... there's something special for those who scroll all the way to the end 😉)"],
    typeSpeed: 40,
    backSpeed: 40,
    backDelay: 1000,
    startDelay: 400,
    loop: true
  });
});
</script>

<div class="container">
  <img src="/images/WhatsApp Image 2024-12-04 at 18.35.41_553e988f.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_2896198e.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.02_180d4cf9.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/nick.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-12-04 at 18.30.32_9408a9bf.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/chiara.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-12-04 at 17.29.41_cb1d7af8.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/skii.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-12-04 at 12.37.46_5df20689.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-12-04 at 18.28.22_0317bc6c.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/grouppic.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/sledge.JPG" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_cd38722a.jpg" class="image" style="cursor: crosshair;">
  <img src="/images/jetty.JPG" class="image" style="cursor: crosshair;">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_5ea38d29.jpg" class="image" style="cursor: crosshair;">
</div>
<style>
  .container {
    width: 100%;
    max-width: 800px;
    margin: 10px auto;
    overflow: hidden;
  }
  .image {
    width: 100%;
    height: 100%;
    margin: 10px 0;
    opacity: 0;
    transform: translateX(-50px);
    transition: opacity 0.8s ease-out, transform 0.8s ease-out;
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
    });
    images.forEach(image => {
      observer.observe(image);
    });
  });
</script>

The secret behind my success. Forever grateful to my family 👨🏻‍👩🏻‍👧🏻‍👦🏻!!!! 

<div class="container1">
  <img src="/images/femily.jpg" class="image1" style="cursor: crosshair;">
</div>
<style>
  .container1 {
    width: 100%;
    max-width: 800px;
    margin: 10px auto;
    overflow: hidden;
  }
  .image1 {
    width: 100%;
    height: 100%;
    margin: 10px 0;
    opacity: 0;
    transform: translateX(50px);
    transition: opacity 0.8s ease-out, transform 0.8s ease-out;
  }
  .image1.show {
    opacity: 1;
    transform: translateX(0);
  }
</style>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    const images = document.querySelectorAll('.image1');
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        } else {
          entry.target.classList.remove('show');
        }
      });
    });
    images.forEach(image => {
      observer.observe(image);
    });
  });
</script>

<!-- Add this inside the <body> tag -->
<div class="photo-album-icon">
  <div class="fill"></div>
</div>

<style>
/* Style for the floating photo album icon */
.photo-album-icon {
  position: fixed;
  top: 50%;
  right: 20px;
  width: 40px;
  height: 100px;
  background-color: #d3d3d3; /* Grey color for submerged effect */
  border-radius: 10px;
  overflow: hidden;
  transform: translateY(-50%);
  z-index: 9999;
}
.fill {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 0;
  background-color: #0078D4; /* Color that fills up as user scrolls */
  transition: height 0.25s ease-out;
}
</style>

<script>
document.addEventListener("scroll", function() {
  const scrollTop = document.documentElement.scrollTop;
  const scrollHeight = document.documentElement.scrollHeight;
  const clientHeight = document.documentElement.clientHeight;
  // Calculate the scroll percentage
  const scrolled = (scrollTop / (scrollHeight - clientHeight)) * 100;
  // Set the height of the fill element based on scroll percentage
  const fillElement = document.querySelector(".photo-album-icon .fill");
  fillElement.style.height = `${scrolled}%`;
});
</script>
