---
title: "❓FAQ Generator"
excerpt: "<img height='600'  width='600' src='/images/summ.png' style='cursor: crosshair;'>"
collection: portfolio
tags: 
  - LLM
  - Fine-tuning
  - NLTK
  - GenAI
  - HuggingFace
---

* Fine-tuned (supervised instruction) **LLaMA-3 8b, LLaMA-2 7b, Mistral 7b, T5, and BART** to generate FAQs based on the website’s content. **HuggingFace** API calls were made to load the models, and **NLTK** tokenizer was used.

<img src="/images/LLMwei.png" style="cursor: crosshair;">

* Scrapped **(Beautiful Soup)** and stored the top 150 US universities’ MS in CS graduate admission requirements in a **JSON** file (dataset creation).

<img src="/images/faqjs.png" style="cursor: crosshair;">

* Performed **QLoRA PEFT** on LLaMA-3 and LLaMA-2 to enhance the quality of the generated FAQs.
* Achieved a **BERT Score of 0.8**, outperforming the baseline T5 transformer with a **50%** increase in accuracy and relevance of generated FAQs.

<img src="/images/qllama3.png" style="cursor: crosshair;">

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/CSCI-499_final_project" target="_blank" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Medium blog:</strong></span> <a href="https://medium.com/@sudarshanasrao/faq-generation-using-large-language-models-88746c9381a6" target="_blank" onclick="trackOutboundLink(this);">
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

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
