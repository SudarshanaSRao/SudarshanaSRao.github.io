# From Data to Decisions

I am an MS student at the University of Southern California, passionate about Artificial Intelligence, Machine Learning, Data Science, and Deep Learning. 

Through my studies and projects, I have developed skills in Large Language Models, Generative AI, Data Engineering, and Data Analysis. I am eager to start my career and learn from experienced teams.

## ✦ [Resume](https://drive.google.com/file/d/1k0NNG9BnLlnowgtQDFwfcsDJePJDyBvx/view?usp=drive_link) ✦ [LinkedIn](https://www.linkedin.com/in/sudarshana-rao/) ✦ ✦ [GAN blog](https://sudarshanagan.blogspot.com/2021/07/everyone-i-am-currently-engineering.html) ✦

## Publications
#### ✦ [Automatic Dent Detection in Automobile Using IR Sensor](https://link.springer.com/chapter/10.1007/978-981-16-9605-3_34) ✦
#### ✦ [Automated garbage disposal system using 8051 microcontroller](https://www.ijamtes.org/VOL-10-ISSUE-8-2020/) ✦

## Projects
### Deep Learning based American Sign Language Recognition

![Preprocess](/assetsimg/preprocess.png)
![Data1](/assetsimg/test-dataset1.png)
![Data2](/assetsimg/dataset.png)

- Developed three classes of **Artificial Neural Network (ANN)** models using the **PyTorch** framework to translate American Sign Language (Kaggle dataset) into a text-based representation.

![arch](/assetsimg/cnnarchitecture.jpg)

- First class is a single generic **Multilayer Perceptron (MLP)** network.
- Second class is two untrained **CNNs (Convolutional Neural Networks)**- a baseline CNN and a custom CNN (with Adam optimizer and L2 regularization).
- Leveraged Transfer Learning using two pre-trained CNNs- **GoogLeNet** and **ResNet18** networks.
- All five models were tested using images captured in real-time and achieved an accuracy of above **90%**.

![google](/assetsimg/googlenet_training.png)

#### ✦ [Code](https://github.com/SudarshanaSRao/EE541-final_project-USC) ✦ 

### ML Based Traffic Light Detection and IR Sensor Based Proximity Sensing for Autonomous Cars

#### ✦ [SSRN ELSEVIER: Publication](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3883931) ✦

![block](/assetsimg/mlblock.png)

- Used **OpenCV2** library to build an automated system to detect and recognize traffic lights for an autonomous car.
- **Hough Gradient Descent** was used to train the model, and **Hough Circles** were drawn around the detected traffic light.
- **IR sensor** (interfaced with an Arduino Uno board) was used to monitor the distance between the autonomous car and nearby obstacles or traffic.
- The system was live-tested on the streets of Bangalore, and excellent results were achieved.

![block](/assetsimg/outputml.png)

#### ✦ [Code](https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/Traffic-light-detection-and-recognition) ✦

## Smart Burglar Alarm

#### ✦ [Publication](https://www.ijamtes.org/VOL-11-ISSUE-7-2021/) ✦

- Detected burglars in real time using **OpenCV2 library, Support Vector Machine, and Histogram of Oriented Gradient**.
- As another line of defense, a PIR sensor interfaced with an Arduino Uno board was utilized for the exact cause to avoid false detection.
- A GSM module was used to send a text message to the homeowner when a burglar is detected.

#### ✦ [Code](https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/Human-detection) ✦

## Exploring Correlation-Driven Feature Selection for Mushroom Classification

- Analyzed the effect of different feature engineering and dimensionality adjustment techniques (performed on the UCI's mushroom dataset) on the performance of various Machine Learning models.

![chi](/assetsimg/chi_scores_.png)

- Pre-processing included feature engineering by **Pearson Correlation Coefficient** method and dimensionality reduction of _173 different species of 61,069 mushrooms_ using **Univariate Feature Selection** and **Principal Component Analysis**.

![f1](/assetsimg/dist1.png)
![f2](/assetsimg/dist2.png)

- Five Machine Learning models were implemented- **Logistic Regression, Support Vector Machine, Gaussian Naive Bayes Classifier, Random Forest Classifier, and Multilayer Perceptron**.
- Cross-validation was performed on the models, and the optimal model for mushroom classification was selected based on the best performance.

![result](/assetsimg/res.png)

#### ✦ [Code](https://github.com/SudarshanaSRao/EE559-final_project-USC) ✦

## Single cell RNA sequencing

![BD](/assetsimg/diagb.png)

- Identified important cells among the dataset and ranked in a hierarchy using **k-means clustering** and **Logistic Regression**.  
- The dataset comprised 2169 cells taken from the neocortex region of a rat's brain and distributed in 20,000 columns. **Principal Component Analysis** was used to reduce 20,000 columns to 3-5 components.
- Visualized the output data through a dynamic 3-D graph using **Plotly**.

![clust](/assetsimg/clusters.png)
  
- Achieved an accuracy of 89.8%.

![BD](/assetsimg/acc.png)

#### ✦ [Code](https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/RNA-sequencing) ✦
