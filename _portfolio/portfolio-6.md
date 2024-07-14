---
title: "🔎Exploring Correlation-Driven Feature Selection for Mushroom Classification"
excerpt: '<br><img src="/images/chi_scores_.png" height="500"  width="500">'
collection: portfolio
---

* Analyzed the effect of different feature engineering and dimensionality adjustment techniques (performed on the UCI's mushroom dataset) on the performance of various Machine Learning models.
* Pre-processing included feature engineering by **Pearson Correlation Coefficient** method and dimensionality reduction of _173 different species of 61,069 mushrooms_ using **Univariate Feature Selection** and **Principal Component Analysis**.
* Performed comprehensive feature analysis and visualization using **Tableau** to highlight the impact of feature engineering and dimensionality reduction techniques. Developed interactive dashboards to illustrate feature distributions, correlations, and their contributions to model performance, enhancing interpretability and data-driven decision-making.

![f1](/images/Picture1.png)
![f1](/images/dist1.png)
![f2](/images/dist2.png)

* Five Machine Learning models were implemented- **Logistic Regression, Support Vector Machine, Gaussian Naive Bayes Classifier, Random Forest Classifier, and Multilayer Perceptron**.
* Cross-validation was performed on the models, and the optimal model for mushroom classification was selected based on the best performance.

![result](/images/res.png)

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/EE559-final_project-USC" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
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
