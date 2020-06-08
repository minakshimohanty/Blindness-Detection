# Blindness Detection Using Deep Learning

# Introduction: 

Diabetic retinopathy is a condition that can cause damage to blood vessels in the retina. This condition can occur in anyone with either type I or type II diabetes. A comprehensive dilated eye examination is conducted to diagnose diabetic retinopathy. In this exam, eye drops are used to dilate the pupils and fundus images are taken to assess blood vessels, optic nerve head and retina.
 
# Objective: 

The goal of the project is to develop a new algorithm that can effectively identify the severity of diabetic retinopathy from fundus images and classify it into the following categories:
0 - No DR
1 - Mild
2 - Moderate
3 - Severe
4 - Proliferative DR
 
# Dataset: 

APTOS and Aravind Eye Hospital, India provides the dataset, through their competition hosted on Kaggle. The link to the competition is: https://www.kaggle.com/c/aptos2019-blindness-detection/overview

# Methodology:

The dataset consists of images acquired by Aravind technicians from multiple clinics, using different cameras. Since the image acquisition conditions were not the same, there is a possibility of variation in the quality of images taken.

Data wrangling: This involves cleaning and pre processing the images for analysis and building the dataset for modeling.
Modeling: Implementing deep learning models, such as, CNN, ResNet-50 and VGG-19

# Results:

In this project, I have implementd 3 deep learning models to help classify the images into different categories of diabetic retinopathy. The accuracy of the my model is 72%. 

Future work in this projest would involve using advances pre-processing and image augmentation techniques to achieve better accuracy.


