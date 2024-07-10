---
layout: archive
title: "Adventurous Me!🤸‍♂️"
permalink: /personal/
author_profile: true
redirect_from:
  - /personal
---

{% include base_path %}

I enjoy ✈️ traveling, 🥾 hiking, 🏏 playing cricket, 🗞️ reading the news, and 🍿 watching movies & 📽️ TV shows in my free time. Hit me up if you want to 🎮 play video games <img src="https://cdn3.emoji.gg/emojis/3139_Xbox.png" width="15px" height="15px" alt="Xbox"> with me!  

Scroll down 🖱️⬇️ to see cool pictures 😎 of me around the world: 
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<style>
#cursor {
  display: inline-block;
  animation: blink 0.7s infinite, move 0.7s steps(30) infinite;
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
@keyframes move {
  from {
    left: 0;
  }
  to {
    left: 1ch; /* Adjust this value based on your font size to match the width of one character */
  }
}
</style>
<p>(Psst... there's something special for those who scroll all the way to the end 😉)(span id="typed-text"></span><span id="cursor">_ /</span></p>
<div class="social-links mt-3 text-center" style="font-size: xx-large"></div>
<script>
document.addEventListener("DOMContentLoaded", function() {
  var typed = new Typed('#typed-text', {
    strings: ["Software Developer", "DevOps Engineer"],
    typeSpeed: 50,
    backSpeed: 50,
    backDelay: 1000,
    startDelay: 500,
    loop: true,
    onComplete: (self) => { 
        // Ensure the cursor appears at the end of the text after each loop
        document.getElementById('cursor').style.left = `${self.el.offsetWidth}px`;
    }
  });
});
</script>

<div class="container">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.02_180d4cf9.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_2896198e.jpg" class="image">
  <img src="/images/nick.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.02_bf5bccb7.jpg" class="image">
  <img src="/images/chiara.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_5ea38d29.jpg" class="image">
  <img src="/images/grouppic.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_cd38722a.jpg" class="image">
  <img src="/images/WhatsApp Image 2024-05-26 at 19.32.03_21151693.jpg" class="image">
</div>
<style>
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

The secret behind my success. Forever grateful to my family 👨🏻‍👩🏻‍👧🏻‍👦🏻!!! 

<div class="container1">
  <img src="/images/femily.jpg" class="image1">
</div>
<style>
  .container1 {
    width: 100%;
    max-width: 800px;
    margin: 20px auto;
    overflow: hidden;
  }
  .image1 {
    width: 100%;
    height: 100%;
    margin: 20px 0;
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
