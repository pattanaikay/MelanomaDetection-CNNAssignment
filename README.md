# MelanomaDetection-CNNAssignment

> Build a Convolutional Neural Network to help with the melanoma cancer detection based on the Skin cancer ISIC The International Skin Imaging Collaboration dataset as part of an assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore. 


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Convolutional Neural Network is made and used on the dataset.
- The project is done as part of coursework in the Deep Learning module. 
- The idea is to build a multi-class classification CNN based model which can accurately detect melanoma.. 
- The International Skin Imaging Collaboration (ISIC) dataset is being used. 
- Data Augmentation is focused on this dataset with dropout layers and normalization. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1) We have cleaned and visualized the data, treated for outlier and imputed values as and when required and prepared the model for training. 

2) The train and test scores for linear regression were 92.12% and 89.43% respectively. 

3) The train and test scores for ridge regression were 92.11% and 89.39% respectively.

4) The train and test scores for lasso regression were 91.74% and 88.70% respectively.

5) As we can see there is not much difference in the model performances in the three cases, however lasso regression model performs ever so slightly better than the other two models. The most important predictor values determined from the analysis were as follows- GrLivArea, OverallQual, MSZoning_RL, MSZoning_RM, TotalBsmtSF 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- keras
- matplotlib
- tensorflow
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@pattanaikay] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
