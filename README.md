# Melanoma-Detection-Assignment
# Project Name
> In this assignment, we built a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)



## General Information

- Problem Statement:
 To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



- Analysis Approach:
  The following will the approach that will be followed to analyze the data and then provide a solution:
  - Data Reading/Data Understanding → Defining the path for train and test images 
  - Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
  - Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
  - Model Building & training : 
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~20 epochs
  - Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
  - Model Building & training on the augmented data :
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~20 epochs
  - Class distribution: Examine the current class distribution in the training dataset 
  - Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
  - Model Building & training on the rectified class imbalance data :
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~30 epochs

Dataset
 All images were provided. It had all the required data 




## Technologies Used
- Python 3
- jupyter
- Tensolflow


## Acknowledgements
Give credit here.
- None.



## Contact
Created by [@piyushrsingh] 
