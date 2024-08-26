---
permalink: /
title: "From Data to Decisions!"
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div>
    <span class="emoji">🔢</span>
    <span class="emoji">👉</span>
    <span class="emoji">💡</span>
    <span class="emoji">📊</span>
    <span class="emoji">📈</span>
</div>
<style>
@keyframes bounce-move {
    0%, 100% {
        transform: translate(0, 0);
    }
    20% {
        transform: translate(100px, 0);
    }
    40% {
        transform: translate(200px, -50px);
    }
    60% {
        transform: translate(300px, 0);
    }
    80% {
        transform: translate(400px, -50px);
    }
}
.emoji {
    display: inline-block;
    animation: bounce-move 4s infinite ease-in-out; 
    font-size: 48px;  /* Adjust the size as needed */
}
.emoji:nth-child(1) { animation-delay: 1.0s; }
.emoji:nth-child(2) { animation-delay: 0.8s; }
.emoji:nth-child(3) { animation-delay: 0.6s; }
.emoji:nth-child(4) { animation-delay: 0.4s; }
.emoji:nth-child(5) { animation-delay: 0.2s; } 
}
</style>

<span class="usc">Welcome to my portfolio website's homepage</span> 😄 I am Sudarshana, a recent MS graduate from the University of Southern California. I am fascinated by the ability of machines to learn from data and uncover patterns that assist us in making data-driven decisions. I am eager to start my career and learn from experienced teams. 
<style>
  @keyframes usc-colors {
    0% {
      background-position: 0% 50%; /* Start gradient at the beginning */
    }
    50% {
      background-position: 100% 50%; /* Move gradient to the right */
    }
    100% {
      background-position: 0% 50%; /* Move gradient back to the start */
    }
  }
  .usc {
    font-size: 24px;
    background: linear-gradient(to right, #ffd700, #C41E3A); /* Cardinal Gold */
    background-size: 200% 200%; /* Ensure the background is large enough to animate */
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: usc-colors 4s infinite ease-in-out; /* Set animation properties */
    display: inline; /* Ensure inline display to avoid unwanted space */
  }
</style>

Through my studies and projects, I have developed skills in Large Language Models, Generative AI, Data Engineering, and Data Analytics. My ideal role involves applying math to develop models or algorithms, analyze data patterns, understand model interpretability, build LLMs, and code data pipelines. Additionally, I am passionate about making AI models safe, reliable, and transparent.    

I am seeking full-time roles and craving challenging opportunities to contribute effectively and grow personally and professionally in an employee-friendly environment.
<div class="separator">
  <div class="shape-separator">
    <div class="shape circle">🛆</div>
    <div class="shape square">🛆</div>
    <div class="shape triangle">🛆</div>
  </div>
</div>

<style>
.separator {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 5px 0;
}
.shape-separator {
  display: flex;
  justify-content: center;
  gap: 20px;
  position: relative;
}
.shape {
  font-size: 36px;
  display: inline-block;
  position: relative;
  z-index: 1;
}
.shape.triangle {
  width: 0;
  height: 0;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-bottom: 30px solid black; /* Adjust the color as needed */
  display: inline-block;
  vertical-align: middle;
  position: relative;
  transform: rotate(180deg); /* Invert the triangle */
}
/* Ripple effect */
.shape::before {
  content: '';
  position: absolute;
  top: 50%;
  left: 50%;
  width: 0;
  height: 0;
  background: rgba(0, 0, 0, 0.2);
  border-radius: 50%;
  transform: translate(-50%, -50%);
  animation: ripple 4s infinite ease-in-out;
}
/* Ripple animation */
@keyframes ripple {
  0% {
    width: 0;
    height: 0;
    opacity: 1;
  }
  50% {
    width: 100px;
    height: 100px;
    opacity: 0;
  }
  100% {
    width: 0;
    height: 0;
    opacity: 1;
  }
}
</style>

# Blogs📝   
<div class="flexcontainer">
  <div>
    <span>✦ A fun and a data-driven analysis on the Summer Olympics:</span> <a href="https://medium.com/@sudarshanasrao/olympics-tableau-3a79b7b49619" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/indy.jpg" width="100px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
    <span>✦ A short, simple, and interesting read on <strong>Generative Adversarial Networks</strong>:</span> <a href="https://sudarshanagan.blogspot.com/2021/07/everyone-i-am-currently-engineering.html" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/1200px-Blogger_icon_2017.svg.png" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
    <span>✦ A descriptive post on my <strong>FAQ Generator</strong> project:</span> <a href="https://medium.com/@sudarshanasrao/faq-generation-using-large-language-models-88746c9381a6" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/image.jpeg" width="80px">
    </a>
  </div>
</div>
<style>
  @keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
  100% {
    transform: scale(1);
  }
}
.pulse {
  animation: pulse 2s infinite ease-in-out;
}
</style>
