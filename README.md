# From Data to Decisions

I am an MS student at the University of Southern California, passionate about Artificial Intelligence, Machine Learning, Data Science, and Deep Learning. 

Through my studies and projects, I have developed skills in Large Language Models, Generative AI, Data Engineering, and Data Analysis. I am eager to start my career and learn from experienced teams.

## ✦ [Resume](https://drive.google.com/file/d/1k0NNG9BnLlnowgtQDFwfcsDJePJDyBvx/view?usp=drive_link) ✦ [LinkedIn](https://www.linkedin.com/in/sudarshana-rao/) ✦

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

[Code](https://github.com/SudarshanaSRao/EE541-final_project-USC)

### ML Based Traffic Light Detection and IR Sensor Based Proximity Sensing for Autonomous Cars

[Publication](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3883931)

![block](/assetsimg/mlblock.png)

- Used OpenCV2 library to build an automated system to detect and recognize traffic lights for an autonomous car.
- Hough Gradient Descent was used to train the model, and Hough Circles were drawn around the detected traffic light.
- IR sensor (interfaced with an Arduino Uno board) was used to monitor the distance between the autonomous car and nearby obstacles or traffic.
- The system was live-tested on the streets of Bangalore, and excellent results were achieved.

![block](/assetsimg/outputml.png)

[Code](https://github.com/SudarshanaSRao/Python-and-its-applications-in-ML/tree/Traffic-light-detection-and-recognition)
