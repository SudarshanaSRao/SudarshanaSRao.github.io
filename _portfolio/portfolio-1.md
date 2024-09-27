---
title: "🗣️Data Visualization Assistant"
excerpt: "<img src='/images/Flowchart.png'>"
collection: portfolio
---

<style>
  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 50px;
  }
  .app-text {
    font-size: 18px;
    margin-right: 15px;
  }
  .app-button {
    background: url('/images/button.png') no-repeat center center;
    background-size: cover;
    width: 150px;
    height: 50px;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    box-shadow: 0 4px #999;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    position: relative;
  }
  .app-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px #666;
  }
  .app-button:active {
    transform: translateY(2px);
    box-shadow: 0 2px #333;
  }
  /* Tooltip styles */
  .tooltip {
    position: absolute;
    background-color: #333;
    color: #fff;
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 12px;
    display: none;
    white-space: nowrap;
    z-index: 1000;
  }
</style>

<div class="container" style="margin-top: -25px;">
  <div class="app-text">
    <h2> Access the app ↪️</h2>
  </div>
  <a href="https://talk-to-your-data.streamlit.app/" target="_blank">
    <button class="app-button" id="appButton">
      <div class="tooltip" id="tooltip">https://talk-to-your-data.streamlit.app/</div>
    </button>
  </a>
</div>

<script>
  const button = document.getElementById('appButton');
  const tooltip = document.getElementById('tooltip');
  button.addEventListener('mouseover', (e) => {
    tooltip.style.display = 'block';
    moveTooltip(e);
  });
  button.addEventListener('mousemove', (e) => {
    moveTooltip(e);
  });
  button.addEventListener('mouseout', () => {
    tooltip.style.display = 'none';
  });
  function moveTooltip(e) {
    tooltip.style.left = e.clientX + 10 + 'px'; // Adjust the position slightly to the right
    tooltip.style.top = e.clientY + 10 + 'px'; // Adjust the position slightly below
  }
</script>

<div class="container" style="margin-top: -25px;">
  <div class="app-text"> <h2> Access the app ↪️</h2> </div>
  <a href="https://talk-to-your-data.streamlit.app/" target="_blank">
    <button class="app-button"></button>
  </a>
</div>

<video width="100%" height="auto" controls>
  <source src="/images/vid.mp4" type="video/mp4">
  Sorry, your browser doesn’t support HTML5 video. Please update your browser or try another one.
</video>

* Launched an **AI-powered app** using **Streamlit**, with a strong emphasis on **data visualization**.

<img src="/images/1sc.png" style="cursor: crosshair;">

* Integrated **Anthropic’s Claude** for natural language processing to facilitate user interaction with data in CSV, PDF, and DOCX formats.
* Developed interactive UI elements for data previews and dynamic visualizations, making complex data insights accessible.

<img src="/images/2sc.png" style="cursor: crosshair;">

* Managed session state to maintain conversation history and context throughout the user interaction.

<img src="/images/3sc.png" style="cursor: crosshair;">

<img src="/images/4sc.png" style="cursor: crosshair;">
  
* Ensured secure API key authentication to protect access to AI services.

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/Talk-to-your-data" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Medium blog:</strong></span> <a href="https://medium.com/@sudarshanasrao/introducing-the-file-conversational-assistant-revolutionizing-document-interaction-with-ai-bf878e5c9ed5" onclick="trackOutboundLink(this);">
      <img class="pulse" height="200px" src="/images/unmanned.png" width="200px">
    </a>
  </div>
</div>
<style>
  .flexcontainer {
    display: flex;
    align-items: center;
    margin-bottom: 20px; /* Adjust the value as needed */  
  }
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
