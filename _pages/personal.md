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

<style>
.containernew {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  margin: 0;
  background-color: #f4f4f9;
}
  .slider-container {
    position: relative;
    width: 80%;
    max-width: 400px;
    overflow: hidden;
    text-align: center;
  }
  .slider-header {
    font-size: 1.5em;
    margin-bottom: 10px;
  }
  .slider-frame {
    display: flex;
    transition: transform 0.5s ease-in-out;
  }
  .slider-frame img {
    width: 100%;
    border-radius: 10px;
  }
  .arrow {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    font-size: 2em;
    color: #333;
    background-color: rgba(255, 255, 255, 0.7);
    border: none;
    cursor: pointer;
    border-radius: 50%;
    padding: 0.2em;
  }
  .arrow:hover {
    background-color: #ddd;
  }
  .arrow-left {
    left: 10px;
  }
  .arrow-right {
    right: 10px;
  }
  .dots-container {
    display: flex;
    justify-content: center;
    margin-top: 10px;
  }
  .dot {
    width: 10px;
    height: 10px;
    margin: 0 5px;
    background-color: #bbb;
    border-radius: 50%;
    cursor: pointer;
  }
  .dot.active {
    background-color: #333;
  }
</style>

<div class="containernew">
<div class="slider-container">
  <div class="slider-header">Browse my collection of video games</div>
  <div class="slider-frame">
    <img src="/images/battlefield.jpg" alt="Image 1">
    <img src="/images/forza.jpg" alt="Image 2">
    <img src="/images/halo.jpg" alt="Image 3">
    <img src="/images/codmw.jpg" alt="Image 4">
    <img src="/images/fifa.jpeg" alt="Image 5">
    <img src="/images/witcher.jpg" alt="Image 6">
    <img src="/images/farcry.jpg" alt="Image 7">
  </div>
  <button class="arrow arrow-left">&#8249;</button>
  <button class="arrow arrow-right">&#8250;</button>
  <div class="dots-container">
    <div class="dot active"></div>
    <div class="dot"></div>
    <div class="dot"></div>
    <div class="dot"></div>
    <div class="dot"></div>
    <div class="dot"></div>
    <div class="dot"></div>
  </div>
</div>

<script>
    const sliderFrame = document.querySelector('.slider-frame');
    const images = document.querySelectorAll('.slider-frame img');
    const dots = document.querySelectorAll('.dot');
    const leftArrow = document.querySelector('.arrow-left');
    const rightArrow = document.querySelector('.arrow-right');
    let currentIndex = 0;
    function updateSlider() {
      sliderFrame.style.transform = translateX(-${currentIndex * 100}%);
      dots.forEach((dot, index) => {
        dot.classList.toggle('active', index === currentIndex);
      });
    }
    function goToNext() {
      currentIndex = (currentIndex + 1) % images.length;
      updateSlider();
    }
    function goToPrevious() {
      currentIndex = (currentIndex - 1 + images.length) % images.length;
      updateSlider();
    }
    function goToSlide(index) {
      currentIndex = index;
      updateSlider();
    }
    rightArrow.addEventListener('click', goToNext);
    leftArrow.addEventListener('click', goToPrevious);
    dots.forEach((dot, index) => {
      dot.addEventListener('click', () => goToSlide(index));
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
    /* Scroll container */
    .scroll-container {
        position: fixed;
        right: 20px;
        top: 50%;
        transform: translateY(-50%);
        width: 40px;
        height: 60vh;
        z-index: 1000;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
/* Zig-zag shaped scroll bar */
.scroll-bar {
    width: 80%;  /* Fixed width */
    height: 100%;
    background-color: rgba(0, 0, 0, 0.2);
    position: relative;
clip-path: polygon(
    0% 50%,   /* Point 1: X=0%, Y=50% (middle of the left edge) */
    25% 0%,   /* Point 2: X=25%, Y=0% (top left corner) */
    50% 50%,  /* Point 3: X=50%, Y=50% (middle of the top edge) */
    75% 100%, /* Point 4: X=75%, Y=100% (bottom right corner) */
    100% 50%, /* Point 5: X=100%, Y=50% (middle of the right edge) */
    75% 0%,   /* Point 6: X=75%, Y=0% (top right corner) */
    50% 50%,  /* Point 7: X=50%, Y=50% (middle of the top edge) */
    25% 100%, /* Point 8: X=25%, Y=100% (bottom left corner) */
    0% 50%    /* Point 9: X=0%, Y=50% (middle of the left edge) */
);
    overflow: hidden;  /* Prevents overflow */
}
    /* Dynamic water-fill effect inside the zig-zag */
    .scroll-fill {
        position: absolute;
        bottom: 0;
        width: 100%;
        height: 0;
        background: linear-gradient(to bottom, #00f260, #045b9b);
        clip-path: inherit;
        animation: water-fill-ripple 4s infinite ease-in-out, water-height 0.3s ease-out;
    }
    /* Ripple effect for water-like animation */
    @keyframes water-fill-ripple {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }
    /* Height adjustment animation (smooth filling up like water) */
    @keyframes water-height {
        0% {
            height: 0;
        }
        100% {
            height: 100%;
        }
    }
    /* Optional message next to the scroll bar */
    .scroll-message {
        margin-top: 10px;
        writing-mode: vertical-rl;
        transform: rotate(180deg);
        font-size: 14px;
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
    <div class="scroll-message" id="scrollMessage"></div>
</div>

<script>
    const messages = [
        "🏋️ Keep going",
        "You're doing great 👌",
        "🧩 Almost there",
        "Just a bit more 🧭",
        "🏆 Victory is near",
        "Secret revealed 👀"
    ];
    const scrollFill = document.getElementById('scrollFill');
    const scrollMessage = document.getElementById('scrollMessage');
    function updateScrollProgress() {
        const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
        const scrollHeight = document.documentElement.scrollHeight - window.innerHeight;
        const scrollProgress = Math.max(0, Math.min(100, (scrollTop / scrollHeight) * 100));
        scrollFill.style.height = `${scrollProgress}%`;
        const messageIndex = Math.min(
            Math.floor((messages.length * scrollProgress) / 100),
            messages.length - 1
        );
        scrollMessage.textContent = messages[messageIndex];
    }
    window.addEventListener('scroll', updateScrollProgress);
    updateScrollProgress();
</script>
