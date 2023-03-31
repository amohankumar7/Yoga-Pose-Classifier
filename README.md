# Yoga-Pose-Classifier

### 1. Problem Statement
Yoga pose estimation is a deep-rooted problem in computer vision that has exposed many challenges in the past. Analyzing human activities is beneficial in many fields like video surveillance, biometrics, assisted living, at-home health monitoring etc.

This project lays the foundation for building such a system by discussing various machine learning and deep learning approaches to accurately classify yoga poses. The project focuses on building machine learning and deep learning models which can accurately classify the yoga pose images. 

The objective of this project is to classify the yoga poses with the highest possible accuracy using deep learning techniques like Convolutional Neural Networks.


### 2. Dataset :
The dataset was created by us as there were no datasets available on internet.The dataset was created by downloading images from google. The dataset folder comprises 10 folders, 1 for each yoga pose. Each pose has approximately 250+ images extracted from Google.

Download Dataset from here: https://drive.google.com/drive/folders/1YwT6rwaVyLiAhO5nTgA5MBDNbNxC-oY-?usp=sharing

### 3. Dependencies :
- Python 3.6
- keras `pip install keras`
- tensorflow `pip install tensorflow`
- OpenCV `pip install opencv-python`
- scikit-learn - `pip install scikit-learn`

Note that keras and tensorflow have their own dependencies. We recommend using [Anaconda](https://www.anaconda.com/) for handling the packages.

### 4. Models Implemented and Steps Followed :

High Level Design:
<p align="center">
  <img src="High Level Design.png" width="600" >
</p>

The following models were implemented:
1. Decision Tree Classifier, Random Forest Classifier, KNN.
2. CNN Models:
    - 1 Convolutional Layer
    - 3 Convolutional Layers - LeakyRelu Activation Function
    - 3 Convolutional Layers - Relu Activation Function
    - 3 Convolutional Layers - Tanh Activation Function
    - 3 Convolutional Layers - Sigmoid Activation Function
    - 3 Convolutional Layers - Elu Activation Function
    - 3 Convolutional Layers - Custom Activation Function
    - 3 Convolutional Layers - ReLU + Custom Activation + Tanh
    - 3 Convolutional Layers - ReLU + Tanh + Custom Activation

The following are steps followed during our project:

1. Importing Required Modules and Understanding the dataset
2. Importing the Images from dataset folder
3. Scaling and splitting the data into Train and Validation.
4. Building the above Models and performing Hyper Parameter Tuning.


### 5. How to run the Code
To run the code:
1. Install all the required packages and dependencies. 
2. Download the dataset and store it with appropriate folder name.
3. Run all the lines of code in the Jupyter Notebook using the 'Run' option or 'Ctrl + Shift'.

## Results:
Accuracies of different CNN models:
<p align="center" padding="10px">
  <img src="Accuracy.png" width="400" >
</p>
<br/>
Final Graph:
<p align="center">
  <img src="Graph.png" width="400" >
</p>




