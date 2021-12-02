# CANCER DETECTION AND DIAGNOSIS
A  website for early cancer detection and diagnosis using machine learning and deep learning.

## Table of Contents
1. [**PROBLEM STATEMENT AND ITS SOLUTION**](#PROBLEM-STATEMENT-AND-ITS-SOLUTION)
2. [**INSTALLATION AND USAGE ON LOCAL SERVER**](#INSTALLATION-AND-USAGE-ON-LOCAL-SERVER)
3. [**WEB INTERFACE**](#Web-Interface)
4. [**IMPLEMENTATION AND BASIC METHODOLOGY**](#IMPLEMENTATION-AND-BASIC-METHODOLOGY)
5. [**METHODOLOGY OF THE PROJECT**](#METHODOLOGY-OF-THE-PROJECT)
6. [**LIBRARIES USED**](#LIBRARIES-USED)


## PROBLEM STATEMENT AND ITS SOLUTION

This project covers the extensive methodologies fitted, issues launch, exploration and future directions in detection of Cancer.  

## INSTALLATION AND USAGE ON LOCAL SERVER
1. Clone the GitHub Repository.
2. Create Virtual Environment.
3. Activate virtual environment.
4. Install Dependencies mentioned in requirements.txt.
5. Run the application.

## Web Interface

#### Dashboard
![Alt Text](/Screenshots/1.PNG)


#### Breast Cancer Diagnosis
![Alt Text](/Screenshots/2.PNG)


#### Cervical Cancer Diagnosis
![Alt Text](/Screenshots/3.PNG)


#### Breast Cancer diagnosis through histopathology images
![Alt Text](/Screenshots/4.PNG)


#### Skin Cancer Prognosis
![Alt Text](/Screenshots/5.PNG)


## IMPLEMENTATION AND BASIC METHODOLOGY
This project covers the extensive methodologies fitted, issues launch, exploration and future directions in detection of Cancer.

Novelty of the project lies in:
To solve the problem by predicting whether the person has Cancer or not using machine learning and Deep Learning.

#### Use or generation of New Dataset 
The project is basically divided into detecting 3 types of Cancer: Skin Cancer, Cervical Cancer and Breast Cancer (by 2 methods) and also divided into prognosis and diagnosis of the respective disease. 
Digitised images, Attributes such as: 1. Clump Thickness, 2. Uniformity of Cell Size, 3. Uniformity of Cell Shape, 4. Marginal Adhesion, 5. Single Epithelial Cell Size, 6. Bare Nuclei, 7. Bland Chromatin, 8. Normal Nucleoli, 9. Mitoses have been taken into account for detection of Breast Cancer.
For diagnosis through histopathology images, convolutional neural network, was trained on patches of 50x50 RGB images, obtained through random crops on the larger 1500x1500 images.
For Skin Cancer, The model was trained on the ISIC 2018 skin cancer(melanoma) dataset, the model uses lesion images and meta-data like gender and age to classify a lesion as malignant or benign.

#### Development of new/hybrid Technology

For Cervical cancer prognosis It predicts likelihood of developing cervical cancer based on lifestyle habits. Used 4 Linear Support vector machines to replicate results of 4 medical tests
for cervical cancer tests namely the Hinselmann test, Schiller test, Cervical cytology, and Biopsy. Accuracies range from 85-90% on the test set for each model.
For Breast Cancer, predicts if a patient(currently having a benign tumor) will develop breast cancer based on features computed features computed using a digitised image of a Fine needle aspirate(FNA) of breast mass.
Also, for another way of diagnosis of Breast Cancer, The model used is a convolutional neural network, was trained on patches of 50x50 RGB images, obtained through random crops on the larger 1500x1500 images. The model scans the input high resolution histopathology image and predicts whether the patch contains a tumor.
For Skin Cancer, The model was trained on the ISIC 2018 skin cancer (melanoma) dataset, the model uses lesion images and meta-data like gender and age to classify a lesion as malignant or benign.

#### Transformation of problem 
Both Unsupervised and Supervised Learning Techniques have been used to efficiently solve the problem of detecting cancer at early stages.

#### Optimization of features
Various feature extraction techniques were used for more accurate results.The mean errors were calculated between the actual times of distant disease occurrence and the times predicted using various prognostic features. Statistical analyses were also done. Majorly, CNN (Convolutional Neural Network) has been built to classify the diagnosis as Malignant or Benign outperforming human accuracy.


## METHODOLOGY OF THE PROJECT 



### LIBRARIES USED

#### NumPy 
NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. 

#### Scikit-learn 
Scikit-learn is a machine learning library in Python. It performs easy-to-use dimensional reduction methods such as Principal Component Analysis (PCA), clustering methods such as k- 10 means, regression algorithms such as logistic regression, and classification algorithms such as random forests (Scikit-learn.org, 2018). 

#### Pandas 
Pandas provides a flexible platform for handling data in a data frame. It contains many open-source data analysis tools written in Python, such as the methods to check missing data, merge data frames, and reshape data structure, etc. (“Pandas”, n.d.). 

#### Flask 
Flask, issued in mid-2010 and developed by Armin Ronacher, is a robust web framework for Python. Flask provides libraries and tools to build primarily simple and small web applications with one or two functions (Das., 2017). 

#### Bootstrap 
Bootstrap is an open-source JavaScript and CSS framework that can be used as a basis to develop web applications. Bootstrap has a collection of CSS classes that can be directly used to create effects and actions for web elements. Twitter’s team developed it in 2011 (“Introduction”, n.d.).
