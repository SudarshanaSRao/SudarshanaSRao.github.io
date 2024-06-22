---
title: "FAQ Generator"
excerpt: "<img height='600'  width='600' src='/images/summ.png'>"
collection: portfolio
---

* Fine-tuned (supervised instruction) **Llama-3 8b, Llama-2 7b, Mistral 7b, T5, and BART** to generate FAQs based on the website’s content.
* Scrapped **(API call using Beautiful Soup)** and stored the top 150 US universities’ MS in CS graduate admission requirements in a **JSON** file (dataset creation).

<img src="/images/faqjs.png">

* Performed **QLoRA PEFT** on Llama-3 and Llama-2 to enhance the quality of the generated FAQs.
* Achieved a 10% increase in accuracy/relevance of generated FAQs compared to a baseline T5 transformer.

<img src="/images/qllama3.png">

<div class="flexcontainer">
    <div>
      <div style="display: flex; justify-content: space-between;">
        <span>✦ <strong>Code:</strong></span>
  </div>
  <div>
    <a href="https://github.com/SudarshanaSRao/CSCI-499_final_project" onclick="trackOutboundLink(this);">
      <img height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
    <div>
      <div style="display: flex; justify-content: space-between;">
        <span>✦ <strong>Medium blog:</strong></span>
  </div>
  <div>
    <a href="https://medium.com/@sudarshanasrao/faq-generation-using-large-language-models-88746c9381a6" onclick="trackOutboundLink(this);">
      <img src="/images/unmanned.png">
    </a>
  </div>
</div>

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
