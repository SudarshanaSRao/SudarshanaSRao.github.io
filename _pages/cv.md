---
layout: archive
title: "CV📄"
excerpt: "CV📄"
permalink: /cv/
author_profile: true
redirect_from:
  - /cv
---

<div class="flexcontainer1">
  <div>
    <span><i>Download my:</i></span> <a href="https://github.com/user-attachments/files/17085887/Sudarshana_Sudheendra_Rao_Resume.pdf" onclick="trackOutboundLink(this);">
      <img class="bounce" height="100px" src="/images/resum.jpg" width="150px">
    </a>
  </div>
</div>
<style>
  .flexcontainer1 {
    display: flex;
    align-items: center;
    justify-content: center;
  }
    .download-container {
    display: flex; /* Ensures content is in a row */
    align-items: center; /* Aligns text and image vertically */
    gap: 10px; /* Adds space between text and image */
  }
  .bounce {
    animation: bounce 1.5s infinite; /* Adjust '2s' to control speed */
  }
  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
      transform: translateY(0);
    }
    40% {
      transform: translateY(-30px);
    }
    60% {
      transform: translateY(-15px);
    }
  }
</style>

Education
==================
<style>
    /* Flexcontainer styling for your main content */
    .flexcontainer {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: flex-start;
    }
    /* Styling for the list item */
    .flexcontainer ul li {
        display: flex;
        justify-content: space-between;
        width: 100%;
        padding-right: 10px;
    }
    /* Thumbnail and popup styling */
    .thumbnail-container2 {
        position: relative;
        display: inline-block;
        cursor: pointer; /* Makes the entire container clickable */
    }
    .thumbnail2 {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 10px;
    }
    .popup-icon2 {
        position: absolute;
        top: 10px;
        right: 5px;
        font-size: 18px;
        color: white;
        background: rgba(0, 0, 0, 0.5);
        border-radius: 50%;
        padding: 2px 5px;
    }
    /* Popup overlay */
    #popup2 {
        display: none;
        position: fixed;
        z-index: 1000;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        align-items: center;
        justify-content: center;
    }
    /* Popup content styling */
    .popup-content2 {
        position: relative;
        width: 600px;
        height: 600px;
        border-radius: 10px;
        overflow: hidden;
    }
    .close-button2 {
        position: absolute;
        top: 35px;
        right: 5px;
        color: #fff;
        font-size: 24px;
        font-weight: bold;
        cursor: pointer;
        background-color: rgba(0, 0, 0, 0.5);
        width: 30px;
        height: 30px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 1;
    }
    /* Popup image styling */
    #popupImage2 {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
    /* Media query to ensure responsiveness */
    @media (max-width: 768px) {
        .flexcontainer {
            flex-direction: column;
            align-items: flex-start;
        }
        .thumbnail-container2 {
            align-self: flex-end;
        }
    }
</style>

<div class="flexcontainer">
  <div>
    <!-- USC logo and main link -->
    <a href="https://usc.edu" onclick="trackOutboundLink(this);">
      <img class="pulse" height="150px" src="/images/usc_logo.png" width="250px">
    </a>
  </div>
  
  <!-- Floating thumbnail with popup functionality, aligned right -->
  <div class="thumbnail-container2" onclick="openPopup2()">
      <img src="/images/Scanned Documents_page-0001.jpg" class="thumbnail2">
      <span class="popup-icon2">&#x2197;</span>
  </div>
  
  <!-- Bullet point section -->
  <div>
    <ul>
      <li>
        <span>Master of Science (MS) in Electrical Engineering (Machine Learning & Data Science), University of Southern California</span>
        <span>2024</span>
      </li>
    </ul>
  </div>
</div>

<!-- Popup overlay for the image -->
<div id="popup2" onclick="closePopup2()">
    <div class="popup-content2" onclick="event.stopPropagation()">
        <span class="close-button2" onclick="closePopup2()">&times;</span>
        <img id="popupImage2" src="/images/Scanned Documents_page-0001.jpg">
    </div>
</div>

<!-- Popup control script -->
<script>
    function openPopup2() {
        document.getElementById('popup2').style.display = 'flex';
    }
    function closePopup2() {
        document.getElementById('popup2').style.display = 'none';
    }
</script>

<style>
    /* Flexcontainer styling for your main content 
    .flexcontainer77 {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: flex-start;
    }
.flexcontainer77 ul li {
    display: flex;
    justify-content: flex-start;
    align-items: center;
}
.degree {
    flex-grow: 1; 
    padding-right: 30px;
}
.year {
    white-space: nowrap; 
}*/
    /* Thumbnail and popup styling */
    .thumbnail-container3 {
        position: relative;
        display: inline-block;
        cursor: pointer; /* Makes the entire container clickable */
    }
    .thumbnail3 {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 10px;
    }
    .popup-icon3 {
        position: absolute;
        top: 10px;
        right: 5px;
        font-size: 18px;
        color: white;
        background: rgba(0, 0, 0, 0.5);
        border-radius: 50%;
        padding: 2px 5px;
    }
    /* Popup overlay */
    #popup3 {
        display: none;
        position: fixed;
        z-index: 1000;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        align-items: center;
        justify-content: center;
    }
    /* Popup content styling */
    .popup-content3 {
        position: relative;
        width: 535px;
        height: 535px;
        border-radius: 10px;
        overflow: hidden;
    }
    .close-button3 {
        position: absolute;
        top: 35px;
        right: 5px;
        color: #fff;
        font-size: 24px;
        font-weight: bold;
        cursor: pointer;
        background-color: rgba(0, 0, 0, 0.5);
        width: 30px;
        height: 30px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 1;
    }
    /* Popup image styling */
    #popupImage3 {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
    /* Media query to ensure responsiveness */
    @media (max-width: 768px) {
        .flexcontainer77 {
            flex-direction: column;
            align-items: flex-start;
        }
        .thumbnail-container3 {
            align-self: flex-end;
        }
    }
</style>

<div class="flexcontainer">
  <div>
    <a href="https://www.bmsce.ac.in/" onclick="trackOutboundLink(this);">
      <img class="pulse" height="140px" src="/images/bmsce_logo.jpg" width="70px">
    </a>
  </div>

<div class="thumbnail-container3" onclick="openPopup3()">
  <img src="/images/Degree Certificate_page-0001.jpg" class="thumbnail3">
  <span class="popup-icon3">&#x2197;</span>
</div>

<div>
  <ul>
    <li>
    <span>Bachelor of Engineering (B.E.) in Electronics and Instrumentation Engineering, B.M.S. College of Engineering</span>
      <span>2022</span>
    </li>
  </ul>
</div>
</div>

<div id="popup3" onclick="closePopup3()">
    <div class="popup-content3" onclick="event.stopPropagation()">
        <span class="close-button3" onclick="closePopup3()">&times;</span>
        <img id="popupImage3" src="/images/Degree Certificate_page-0001.jpg">
    </div>
</div>

<script>
    function openPopup3() {
        document.getElementById('popup3').style.display = 'flex';
    }
    function closePopup3() {
        document.getElementById('popup3').style.display = 'none';
    }
</script>

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
  animation: pulse 3s infinite ease-in-out;
}
</style>

Skills
==================
* ### Programming Languages
  * Python  \|  SQL  \|  MySQL  \|  MongoDB Atlas  \|  C++  \|  C  \|  HTML  \|  CSS  \|  JavaScript  \|  R  \|  MATLAB  \| XML  \|  PostgreSQL  \|  ESRI ArcGIS  \|  BigQuery  \|  UiPath studio (Robotics Process Automation) 

* ### ML Frameworks & Libraries
  * Streamlit GUI  \|  Beautiful Soup  \|  PyTorch  \|  TensorFlow  \| NumPy \|  Keras  \|  Scikit-learn  \|  SciPy  \|  Plotly  \|  Matplotlib  \|  Seaborn  \|  Pandas  \|  HuggingFace  \|  Kaggle  \|  LangChain  \|  OpenCV

* ### Tools
  * Git  \|  MS Azure  \|  GCP  \|  MS Office  \|  LLMOps  \|  MLOps  \|  DataOps  \|  Conversational Agents  \|  Multi-modal Agentic Workflows  \|  Google Sheets  \|  Jupyter Notebook (Anaconda navigator)  \|  VS Code  \|  CI/CD  \|  Tableau  \|  LATEX  \|  Data Structues and Algorithms  \|  ETL  \|  Power BI  

Work Experience
==================
<div class="flexcontainer">
  <div>
    <a href="https://sail.usc.edu/" onclick="trackOutboundLink(this);">
      <img class="pulse" height="150px" src="/images/usc_logo.png" width="250px">
    </a>
  </div>
 </div>
 
### Student worker at University of Southern California, Los Angeles [October 2022-Present]
_{August 2024-Present}_
* Researching and implementing **LLM** use cases in **Data Analytics**.   

_{May 2023-August 2024}_ (**Disney** sponsored project)
* Researched and analyzed human interaction with an AI (Nobu) to improve its Automatic Speech Recognition (ASR).  
* Managed the interaction sessions (data collection) by assigning participants to the respective time slots.
* Project: Speech quality assessment for automatic speech recognition. 

_{October 2022-May 2023}_ (**Apple** funded project)
* Worked at the **S**ignal **A**nalysis and **I**nterpretation **L**aboratory (**SAIL** under the **SIPI**- **S**ignal and **I**mage **P**rocessing **I**nstitute) to annotate audio files.    
* These annotations will train a Machine Learning model to identify, classify, and filter out the noise in recorded conversations.
* Appeared at the Interspeech 2023 conference under the research paper title- "Understanding Spoken Language Development of Children with ASD Using Pre-trained Speech Embeddings".

<style>
    /* Flexcontainer styling for your main content */
    .flexcontainer88 {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: flex-start;
    }
    /* Thumbnail and popup styling */
    .thumbnail-container4 {
        position: relative;
        display: inline-block;
        cursor: pointer; /* Makes the entire container clickable */
    }
    .thumbnail4 {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 10px;
    }
    .popup-icon4 {
        position: absolute;
        top: 10px;
        right: 5px;
        font-size: 18px;
        color: white;
        background: rgba(0, 0, 0, 0.5);
        border-radius: 50%;
        padding: 2px 5px;
    }
    /* Popup overlay */
    #popup4 {
        display: none;
        position: fixed;
        z-index: 1000;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        align-items: center;
        justify-content: center;
    }
    /* Popup content styling */
    .popup-content4 {
        position: relative;
        width: 535px;
        height: 535px;
        border-radius: 10px;
        overflow: hidden;
    }
    .close-button4 {
        position: absolute;
        top: 35px;
        right: 5px;
        color: #fff;
        font-size: 24px;
        font-weight: bold;
        cursor: pointer;
        background-color: rgba(0, 0, 0, 0.5);
        width: 30px;
        height: 30px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 1;
    }
    /* Popup image styling */
    #popupImage4 {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
    /* Media query to ensure responsiveness */
    @media (max-width: 768px) {
        .flexcontainer88 {
            flex-direction: column;
            align-items: flex-start;
        }
        .thumbnail-container4 {
            align-self: flex-end;
        }
    }
</style>
  
 <div class="flexcontainer88">
  <div>
    <a href="https://ennvee.com/" onclick="trackOutboundLink(this);">
      <img class="pulse" height="100px" src="/images/ennlogog.jpeg" width="70px">
    </a>
  </div>

<div class="thumbnail-container4" onclick="openPopup4()">
    <img src="/images/Internship_page-0001.jpg" class="thumbnail4">
    <span class="popup-icon4">&#x2197;</span>
</div>
</div>

<div id="popup4" onclick="closePopup4()">
    <div class="popup-content4" onclick="event.stopPropagation()">
        <span class="close-button4" onclick="closePopup4()">&times;</span>
        <img id="popupImage4" src="/images/Internship_page-0001.jpg">
    </div>
</div>

<script>
    function openPopup4() {
        document.getElementById('popup4').style.display = 'flex';
    }
    function closePopup4() {
        document.getElementById('popup4').style.display = 'none';
    }
</script>

### Summer Intern at ennVee Solutions Private Limited, Bangalore [Summer 2021]
  *  Developed a bot (using UiPath studio ReFramework) for E-commerce companies to generate purchase order I.D.s against orders received online, thus ensuring on-time delivery of products.
  *  Programmed a bot to automatically fill Google forms by taking input (applicant's details) from an Excel sheet, thereby reducing the hiring process time by 25%.
  *  Built a bot to extract specific emails based on textual metadata, improving employee productivity; ported the extracted data to Excel spreadsheets for analysis.
  *  Implemented a bot to extract identified data from websites into M.S. Excel, saving 15% of the buyer's time.
  *  Coded a bot to automatically generate complaint tickets and assign tickets to responsible personnel, enhancing customer service.
  
Leadership & Involvement
==================
* Course Producer for the Database Systems (CSCI-585) course under Prof. Saty's guidance during the _Spring 2024_ term. Held office hours, mentored, and evaluated homework and exams for a class of 300 students.
* Project Coordinator of The Department of Electronics & Instrumentation Engineering during the National Level Annual Technical Symposium Phase Shift 2021, organized in B.M.S. College of Engineering (BMSCE).
* Student Volunteer of Mitsubishi Electric Cup- National Level Competition for Factory Automation held at BMSCE.

Awards
==================
<style>
    .content-container {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .thumbnail-container {
        position: relative;
        display: inline-block;
        margin-left: 20px;
        cursor: pointer; /* Makes the entire container clickable */
    }
    .thumbnail {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 10px;
    }
    .popup-icon {
        position: absolute;
        top: 5px;
        right: 5px;
        font-size: 18px;
        color: white;
        background: rgba(0, 0, 0, 0.5);
        border-radius: 50%;
        padding: 2px 5px;
    }
    #popup {
        display: none;
        position: fixed;
        z-index: 1000;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        align-items: center;
        justify-content: center;
    }
    .popup-content {
        position: relative;
        width: 500px;
        height: 500px;
        border-radius: 10px;
        overflow: hidden;
    }
    .close-button {
        position: absolute;
        top: 10px;
        right: 10px;
        color: #fff;
        font-size: 24px;
        font-weight: bold;
        cursor: pointer;
        background-color: rgba(0, 0, 0, 0.5);
        width: 30px;
        height: 30px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 1;
    }
    #popupImage {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
</style>

<div class="content-container">
    <p>✔ Won second prize in a Computer Science seminar on satellite communication held at the Sumeru Fest in RV PU College.</p>
    <div class="thumbnail-container" onclick="openPopup()">
        <img src="/images/Trophy.jpg" alt="Satellite Communication Seminar" class="thumbnail"> 
        <span class="popup-icon">&#x2197;</span>
    </div>
</div>
<div id="popup" onclick="closePopup()">
    <div class="popup-content" onclick="event.stopPropagation()">
        <span class="close-button" onclick="closePopup()">&times;</span>
        <img id="popupImage" src="/images/Trophy.jpg" alt="Full size image"> 
    </div>
</div>

<script>
    function openPopup() {
        document.getElementById('popup').style.display = 'flex';
    }
    function closePopup() {
        document.getElementById('popup').style.display = 'none';
    }
</script>

<style>
    .content-container1 {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .thumbnail-container1 {
        position: relative;
        display: inline-block;
        margin-left: 20px;
        cursor: pointer; /* Makes the entire container clickable */
    }
    .thumbnail1 {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 10px;
    }
    .popup-icon1 {
        position: absolute;
        top: 10px;
        right: 5px;
        font-size: 18px;
        color: white;
        background: rgba(0, 0, 0, 0.5);
        border-radius: 50%;
        padding: 2px 5px;
    }
    #popup1 {
        display: none;
        position: fixed;
        z-index: 1000;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        align-items: center;
        justify-content: center;
    }
    .popup-content1 {
        position: relative;
        width: 600px;
        height: 600px;
        border-radius: 10px;
        overflow: hidden;
    }
    .close-button1 {
        position: absolute;
        top: 35px;
        right: 5px;
        color: #fff;
        font-size: 24px;
        font-weight: bold;
        cursor: pointer;
        background-color: rgba(0, 0, 0, 0.5);
        width: 30px;
        height: 30px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 1;
    }
    #popupImage1 {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
</style>

<div class="content-container1">
    <p>✔ Qualified in the 12th grade state-level examination with distinction and scored 100/100 in mathematics.</p>
    <div class="thumbnail-container1" onclick="openPopup1()">
        <img src="/images/Second PUC math.jpg" alt="Second PUC Math" class="thumbnail1">
        <span class="popup-icon1">&#x2197;</span>
    </div>
</div>
<div id="popup1" onclick="closePopup1()">
    <div class="popup-content1" onclick="event.stopPropagation()">
        <span class="close-button1" onclick="closePopup1()">&times;</span>
        <img id="popupImage1" src="/images/Second PUC math.jpg" alt="Full size image PUC Math">
    </div>
</div>

<script>
    function openPopup1() {
        document.getElementById('popup1').style.display = 'flex';
    }
    function closePopup1() {
        document.getElementById('popup1').style.display = 'none';
    }
</script>
