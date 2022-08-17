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
1) We have loaded and visualized the data and built a first layer with max-pooling, dropout layers and using functions like relu and softmax. 

2) Low model accuracies were observed and model overfitting was observed and subsequently data augmentation was used to overcome the model overfitting. 

3) Data augmentation improved model overfitting cases.

4) Class imbalance was checked and then Augmentor library was used woth 500 additional images to improve model accuracy and treat for model overfitting.


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
