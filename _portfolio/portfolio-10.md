---
title: "🗿Mythological Storyteller"
excerpt: "<img src='/images/mahabharata_finetune_pipeline.png' height='300' width='300' style='cursor: crosshair;'>"
collection: portfolio
tags: 
  - Web app
  - AI
  - NLP
  - HuggingFace
  - LLM
  - GPT Neo
  - Gradio GUI
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
    background: url('https://github.com/user-attachments/assets/8cec4a21-5cd9-4349-84fe-2a29fabdfc70') no-repeat center center;
    background-size: cover;
    width: 200px;  /* Adjusted size */
    height: 50px;  /* Adjusted size */
    border: none;
    border-radius: 25px;
    cursor: pointer;
    box-shadow: 0 4px #999;  /* 3D shadow effect */
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .app-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px #666;
  }
  .app-button:active {
    transform: translateY(2px);
    box-shadow: 0 2px #333;
  }
</style>

<div class="container" style="margin-top: -25px;">
  <div class="app-text"> <h2> Access the web app ↪️</h2> </div>
  <a href="https://huggingface.co/spaces/Samurai719214/GPTNeo-storyteller" target="_blank">
    <button class="app-button"></button>
  </a>
</div>

<div class="flexcontainer45r" style="margin-top: 20px;">
  <div>
        <span>Hosted this fine-tuned model on <strong>HuggingFace</strong>: - </span> <a href="https://huggingface.co/Samurai719214/gptneo-mythology-storyteller" target="_blank" onclick="trackOutboundLink(this);">
      <img class="pulse" height="100px" src="https://github.com/user-attachments/assets/cbee90fe-66ed-42b7-9b8f-28fd0659a34e" width="100px">
    </a>
  </div>
</div>

<style>
  .flexcontainer45r {
    display: flex; 
    align-items: center;
    justify-content: center;
  }
</style>

- Fine-tuned **GPT-Neo 125M** using a custom training pipeline that integrated structured mythological metadata with narrative text.

<img src="/images/HF_out.png" style="cursor: crosshair;">

- Employed data augmentation techniques and a sliding-window approach to expand limited [_Kaggle datasets_](https://www.kaggle.com/datasets/shivanshuman/the-mahabharata-summary){:target="_blank"}.

<img src="/images/HF_ggraph.png" style="cursor: crosshair;">

- Hosted this model on HuggingFace hub, utilizing **PyTorch**, **Transformers**, and mixed-precision (fp16) training to ensure efficient resource utilization and scalable deployment.

- Deployed an interactive **Gradio** web app that accepts incomplete story excerpts, automatically prepends contextual instructions, and leverages sampling-based inference (with parameters like temperature, top-p, and no-repeat n-gram constraints) for creative text generation.

<img src="/images/HF_gradio1.png" style="cursor: crosshair;">
<img src="/images/HF_gradio2.png" style="cursor: crosshair;">

- Evaluated model performance using quantitative metrics such as **ROUGE score** and fine-tuning hyperparameters (learning rate, batch size, warmup steps) to balance overfitting and generalization.

<img src="/images/HF_train.png" style="cursor: crosshair;">

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/GPTNeo_storyteller" target="_blank" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
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
