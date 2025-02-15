---
title: "🕹️Steam Sales Analysis"
tags: 
  - Data pipeline
  - ETL
  - Tableau dashboard
  - Docker
  - Cloud computing
  - Python
  - MySQL
  - Automation
  - Data Analytics
  - DataOps
excerpt: "<img src='/images/steamstore-etl.drawio.png' style='cursor: crosshair;'>"
collection: portfolio
---

<div class="flexcontainer45">
  <div>
        <span>Created and deployed a (open-source contribution) <strong>Python PyPI package</strong> (library): - </span> <a href="https://pypi.org/project/steamstore-etl/" target="_blank" onclick="trackOutboundLink(this);">
      <img class="pulse" height="70px" src="/images/py-pkgs-hex.png" width="70px">
    </a>
  </div>
</div>
<style>
  .flexcontainer45 {
    display: flex; 
    align-items: center;
    justify-content: center;
  }
</style>

* Developed and implemented a comprehensive **ETL pipeline** for extracting, transforming, and loading game-related metadata, details, and sales figures from Steamspy and Steam APIs (requests library) into a **MySQL database** on **Aiven Cloud**.

<img src="/images/steam_logo_banner.jpg" style="cursor: crosshair;">

* Engineered data retrieval and processing with batch processing and bulk inserts to ensure accurate and efficient data ingestion and validation.
* Designed **interactive Tableau dashboard** to visualize data dynamically, providing actionable insights into gaming trends and sales performance (showcasing **KPIs**).

<div class='tableauPlaceholder' id='viz1725408615923' style='position: relative'>
<noscript>
  <a href='#'> <img alt='Dashboard 4 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;SteamAnalysis_17254061314020&#47;Dashboard4&#47;1_rss.png' style='border: none' /> </a>
</noscript>
<object class='tableauViz'  style='display:none;'> 
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SteamAnalysis_17254061314020&#47;Dashboard4' /> <param name='tabs' value='no' /> <param name='toolbar' value='yes' /> <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;SteamAnalysis_17254061314020&#47;Dashboard4&#47;1.png' /> <param name='animate_transition' value='yes' /> <param name='display_static_image' value='yes' /> <param name='display_spinner' value='yes' /> <param name='display_overlay' value='yes' /> <param name='display_count' value='yes' /> <param name='language' value='en-US' /> <param name='filter' value='publish=yes' />
</object>
</div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1725408615923');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

* Created a **command-line interface (CLI)** for managing data ingestion processes, with commands for cleaning, fetching, and processing data, including customizable options for batch size and data handling.
* Configured and maintained database integration, ensuring proper connection and storage of data within the MySQL database.

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/DataForgeOpenAIHub/Steam-Sales-Analysis" target="_blank" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Medium blog:</strong></span> <a href="https://medium.com/@sudarshanasrao/steam-sales-insight-data-driven-analysis-and-visualization-pipeline-803862e5f555" target="_blank" onclick="trackOutboundLink(this);">
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
