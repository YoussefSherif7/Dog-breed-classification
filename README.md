# Dog-breed-classification
Dog breed classification using Convolutional Neural Networks
### Table of contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This project is built using python and a few libraries. 
The libraries used are: [opencv-python,h5py,matplotlib,numpy,scipy,tqdm,scikit-learn,keras,tensorflow]

## Project Motivation<a name="motivation"></a>
This is my capstone project for the Udacity data science program, very proud to have finally reached this milestone!!

This project develops the understanding of convolutional neural networks applications, where i applied and understood how classifiers, convolutional layers, as well as 
transfer learning in order to test, modify, and increase the accuracy of model predictions.
The end goal of this project, is to accept any user-supplied image as input. 
If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, 
it will provide an estimate of the dog breed that is most resembling. 

The project is divided into 5 sections
### 1-Importing datasets
Where i loaded in the datasets, studied some of their charecteristics and populate my needed variables.

### 2-Detecting humans
Implemented and tested the accuracy of a human face detector

### 3-Detecting dogs
Implemented and tested the accuracy of a dog class detector

### 4-CNN to Classify Dog Breeds
In this step, I create a CNN that classifies dog breeds from scratch.

### 5-Use CNN to Classify Dog Breeds
Performed predictions on dog breed from images

### 6-Transfer Learning
Created a CNN to Classify Dog Breeds (using Transfer Learning)

### 7-Algorithm and testing
Combined everything in an algorithm that performs dog breed classification

## File Descriptions<a name="files"></a>
This repository includes the python notebook where the implementation exists named dog_app.ipynb, and this ReadMe.md file


## Results<a name="results"></a>
The final CNN model implemented using InceptionV3 showed 78.1% accuracy.
A sample of the results can be seen below:

![image](https://user-images.githubusercontent.com/71082811/226230212-254f40f7-fcc3-422f-ba31-7129521b67c5.png)
![image](https://user-images.githubusercontent.com/71082811/226230229-e33f7ee5-9b78-4734-8376-d4c5b6502f49.png)

You can check my blogpost on this project on medium [here](https://medium.com/@youssefsherief/dog-breed-classification-using-convolutional-neural-networks-c5452ebce00d).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Thanks to the Udacity data science team for their support throughout this program. All credits go to Udacity for for the code and images used.
