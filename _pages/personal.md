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

<style>
.scroll-container {
    position: fixed;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    width: 20px;
    height: 60vh;
    z-index: 1000;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.scroll-bar {
    width: 100%;
    height: 100%;
    background-color: rgba(224, 224, 224, 0.3);
    border-radius: 10px;
    position: relative;
    overflow: hidden;
    border: 1px solid rgba(0, 0, 0, 0.1);
}
.scroll-fill {
    width: 100%;
    height: 0;
    background: linear-gradient(to right, #00f260, #0575e6);
    position: absolute;
    bottom: 0;
    transition: height 0.3s ease;
    animation: glowing 1.5s infinite alternate;
}
@keyframes glowing {
    0% { 
        box-shadow: 0 0 10px rgba(0, 242, 96, 0.7), 
                    0 0 15px rgba(5, 117, 230, 0.7);
    }
    100% { 
        box-shadow: 0 0 20px rgba(0, 242, 96, 0.9), 
                    0 0 30px rgba(5, 117, 230, 0.9);
    }
}
.scroll-message {
    margin-top: 10px;
    writing-mode: vertical-rl;
    transform: rotate(180deg);
    font-size: 12px;
    font-weight: bold;
    color: #444;
    text-align: center;
    white-space: nowrap;
}
</style>

<div class="scroll-container">
<div class="scroll-bar">
    <div class="scroll-fill" id="scrollFill"></div>
</div>
<div class="scroll-message" id="scrollMessage">Swipe to reveal the secret👀</div>
</div>

<script>
const messages = [
    "🏋️Keep going",
    "You're doing great👌", 
    "🧩Almost there", 
    "Just a bit more🧭",
    "🏆Victory is near"
];
const scrollFill = document.getElementById('scrollFill');
const scrollMessage = document.getElementById('scrollMessage');
function updateScrollProgress() {
    // Use documentElement.scrollHeight to get total scrollable height
    const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
    const scrollHeight = document.documentElement.scrollHeight - window.innerHeight;
    // Calculate scroll percentage
    const scrollProgress = Math.max(0, Math.min(100, (scrollTop / scrollHeight) * 100));
    // Update scroll fill height
    scrollFill.style.height = `${scrollProgress}%`;
    // Update motivational message
    const messageIndex = Math.floor((messages.length * scrollProgress) / 100);
    scrollMessage.textContent = messages[Math.min(messageIndex, messages.length - 1)];
}
// Add scroll event listener
window.addEventListener('scroll', updateScrollProgress);
// Initial call to set up initial state
updateScrollProgress();
</script>
