---
permalink: /
title: "From Data to Decisions! 🔢 👉 💡📊📈"
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my portfolio website's homepage 😄 I am Sudarshana, a recent MS graduate from the University of Southern California. I am passionate about Artificial Intelligence, Machine Learning, Data Science, and Deep Learning. 

Through my studies and projects, I have developed skills in Large Language Models, Generative AI, Data Engineering, and Data Analytics. I am eager to start my career and learn from experienced teams.

I am seeking full-time roles and craving challenging opportunities to contribute effectively and grow personally and professionally in an employee-friendly environment.

<div class="hero-section">
  <img id="hero-image" src="/images/MLDL.jpg" class="fade-in" alt="AI and Human Interaction">
  <div class="hero-text">
    <h1>Bridging the Gap Between Human and Machine Intelligence</h1>
  </div>
</div>
<style>
.hero-section {
  position: relative;
  text-align: center;
  color: white;
}
.hero-section img {
  width: 100%;
  height: auto;
  opacity: 0;
}
.hero-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.fade-in {
  opacity: 0;
  transition: opacity 2s;
}
}
</style>
<script>
  document.addEventListener("DOMContentLoaded", function() {
  const image = document.getElementById("hero-image");
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        image.style.opacity = 1;
      }
    });
  });
  observer.observe(image);
});
</script>

# Blogs📝   
<div class="flexcontainer">
  <div>
    <span>✦ A short, simple, and interesting read on <strong>Generative Adversarial Networks</strong>:</span> <a href="https://sudarshanagan.blogspot.com/2021/07/everyone-i-am-currently-engineering.html" onclick="trackOutboundLink(this);">
      <img height="30px" src="/images/1200px-Blogger_icon_2017.svg.png" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
    <span>✦ A descriptive post on my <strong>FAQ Generator</strong> project:</span> <a href="https://medium.com/@sudarshanasrao/faq-generation-using-large-language-models-88746c9381a6" onclick="trackOutboundLink(this);">
      <img height="30px" src="/images/image.jpeg" width="80px">
    </a>
  </div>
</div>
