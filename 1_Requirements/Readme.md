# Requirements

## Introduction

Coronavirus disease (COVID-19) is a newly found coronavirus-caused infectious disease. Most people infected with the COVID-19 virus will experience mild to moderate respiratory disease and recover without any special treatment being required. Elderly people as well as those with underlying health problems such as diabetes, chronic respiratory disease, heart disease are diseases that can cause a severe illness . It is affects in different ways to different people .Many people can have mild to moderate illness and they can recover without any treatment. COVID-19 is divided into 3 phases : -

Phase 1 - In phase 1 common symptoms are:

     * Fever
     * Dry Cough
     * Tiredness
     
Phase 2 - In phase 2 common symptoms are:

     * Pains and aches
     * Sore throat
     * Diarrhoea
     * Conjunctivitis
     * Headache
     * Loss of taste or smell
     * A rash on skin, or discolouration of fingers or toes
     
Phase 3 –In phase 3 some serious symptoms are:

     * Difficulty in breathing
     * Pain in chest or Chest Pressue
     * Loss of speech
     * Loss of movement
     
As the number of coronavirus patients are increasing day by day then we need a fast and efficient method to diagnose a patient. Artificial Intelligence is the best solution for diagnosis. 

## Problem Statement 
Availability of dataset is the main issue whenever a new disease comes. The predictions can’t be made on small dataset which might not give the accurate results.Through this model we can also make predictions using less dataset also with robust accuracy.
Developing and Implementing a Model which will give robust predictions on a smaller dataset.

## Objective and Challenges 
Design an efficient CNN based Deep learning Combined Model for X-Ray images and CT Images. 
* In CNN Large volume of data is required with more hyper-parameter tuning to extract optimal features.
* Robust accuracy on smaller dataset.

![](https://github.com/ShivaniSharma11/ShivaniProject/blob/master/Images/images.jpg)

![](https://github.com/ShivaniSharma11/ShivaniProject/blob/master/Images/images%20(1).jpg)

## Research

* In this paper author has developed a model for COVID-19 detection using Chest X-ray images. Developed a model using DarkNet model using YOLO and achieved an accuracy of 98.08% for binary classification and 87.02% for multi-class classification. (https://doi.org/10.1016/j.cmpb.2020.105581)
* In this paper author has developed a model for COVID19 classification using chest X-ray images. He took different images of  tuberculosis (TB), pneumonia , COVID-19 and normal. Used a model called DenseNet-161 and achieved  an accuracy of 98.9%.(doi: https://doi.org/10.1101/2020.06.21.20136598)
* In this paper authors has used 5 pretrained models for covid detection using chest X-ray images of bacterial pneumonia, normal ,COVId-19 and ,viral pneumonia. They achieved the best accuracy on ResNet50 of 99.7%. (arXiv:2003.10849v3)
* In this paper they tried to detect COVID‐19 detection using chest x‐ ray images using deep convolutional neural networks (DCNN). The dataset contained images COVID-19, Viral pneumonia and Normal Chest X-ray Images.They used a Inception V3 with transfer learning for detection anc achieved an accuracy more than 98%(https://doi.org/10.1101/2020.05.01.20088211)
* In this paper author has used different pre-trained models  ResNet19, denseNet-121, ResNet50 and SqueezNet for COVID19 detection using chest X-ray and CT scan images. In which they achieved the best accuracy of 97.5%.(https://doi.org/10.1016/j.cmpb.2020.105581)
* In this paper authors has developed multi model for COVID-19 diagnosis using  CT scan images and X-Ray images. They used two pretrained models ResNet-50 and VGG-16 for diagnosis and achieved 95.38% of accuracy in CT scan images and 98.97% of accuracy in X-Ray images.(https://doi:10.1016/j.compbiomed.2020.103792)

## Cost and Features and Timeline

* This disease came into at the end of 2019 and still its all over the world. 
* This is basically affecting the lungs in severe cases and turning into viral pneumonia.
* People found a manual way in 2020 for its detection which was taking 2-3 days for detection.
* Then people tried to find more alternative and fast solutions then detection of COVID19 started by using CT Scan and XRay images.
* As CT Scan is costlier than X-Ray images so some people can afford only X-Rays.
* So we tried to diagnose using CT Scan images and X-Ray images. 
* Doctors then analyse those images and try to find whether a person is affected from COVID19 or not. 

* This project will save one step where doctors does't need to analyse that image. This will reduce the timing and also the cost too. 

![](https://github.com/ShivaniSharma11/ShivaniProject/blob/master/Images/Covid-19-and-X-Ray.jpg)

## SWOT ANALYSIS
![](https://github.com/ShivaniSharma11/ShivaniProject/blob/master/Images/Swot.png)

## Define the System
  Project for COVID-19 Diagnosis using Chest X-Ray and CT Scan images
  
# 4W's and 1'H
## Who:
This project can be used in hospitals which will give a relief to doctors and saves the time of doctors as well patients.

## Where:
This can be used in hospitals, Industries by using the body scanners, Airports etc for a quick test. 

## When:
It can be used at any time to check whether a person is affected from COVID-19 or not. 

## What:
They can play this game and enjoy the free time by winning the game.  

## How:
* These steps are temporary for now as it is just an application that is developed partially. 
* 1. Download this game from the github
* 2. Unzip the file.
* 3. Open this file in Pycharm or Google Colab etc.
* 4. If it is opened in Google colab then no need to download the modules otherwise download modules using terminal.
* 5. Command to download the module is  - " pip install packagename ".
* 6. Download the dataset and save it into your system and change the path in the code as per your dataset location.
* 7. Run the code and train the model. 
* 8. You'll get the output.

## Detail requirements

## High Level Requirements:

ID | Description | Status(Implemented / Future)
------------ | ------------- | ----------
01 |  Load dataset of images from the path | Implemented  
02 |  Preprocessing of each image | Implemented
03 |  Split the data into Test and train | Implemented
04 |  Train the Model | Implemented
05 |  Test the Model  | Implemented

## Low level Requirements


ID | Description | Status(Implemented / Future)
------------ | ------------- | ----------
01 | Load dataset of images from the path | Implemented
02 | Preprocessing of each image | Implemented
03 | Rescaling of each image | Implemented
04 | labeling each image | Implemented 
05 | Split the data into Test and Train | Implemented
06 | Train the Model | Implemented
07 | Save the best Model | Implemented
08 | Test the Model | Implemented 

