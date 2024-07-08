---
title: "FAQ Generator"
excerpt: "<img height='600'  width='600' src='/images/summ.png'>"
collection: portfolio
---

* Fine-tuned (supervised instruction) **Llama-3 8b, Llama-2 7b, Mistral 7b, T5, and BART** to generate FAQs based on the website’s content.
* Scrapped **(API call using Beautiful Soup)** and stored the top 150 US universities’ MS in CS graduate admission requirements in a **JSON** file (dataset creation).

<img src="/images/faqjs.png">

* Performed **QLoRA PEFT** on Llama-3 and Llama-2 to enhance the quality of the generated FAQs.
* Achieved a **BERT Score of 0.8**, outperforming the baseline T5 transformer with a 50% increase in accuracy and relevance of generated FAQs.

<img src="/images/qllama3.png">

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/CSCI-499_final_project" onclick="trackOutboundLink(this);">
      <img class="bounce" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Medium blog:</strong></span> <a href="https://medium.com/@sudarshanasrao/faq-generation-using-large-language-models-88746c9381a6" onclick="trackOutboundLink(this);">
      <img class="bounce1" height="200px" src="/images/unmanned.png" width="200px">
    </a>
  </div>
</div>
<style>
  .flexcontainer {
    display: flex;
    align-items: center;
    margin-bottom: 20px; /* Adjust the value as needed */  
  }
  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% { transform: rotate(0deg); }
    40% { transform: rotate(10deg); }
    60% { transform: rotate(7deg); }  
  }
  .bounce {
    display: inline-block;
    animation: bounce 1.3s ease infinite;
    transform-origin: center; /* Pivot around the top center */
  }
    @keyframes bounce1 {
    0%, 20%, 50%, 80%, 100% { transform: rotate(0deg); }
    40% { transform: rotate(-10deg); }
    60% { transform: rotate(-7deg); }  
  }
  .bounce1 {
    display: inline-block;
    animation: bounce 1.3s ease infinite;
    transform-origin: center; /* Pivot around the top center */
  }
</style>

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
