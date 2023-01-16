# CNN-Melanoma-Detection
# Deep Learning - Melanoma Detection Assignment
> Melanoma is a type of skin cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. Repository contains a deep learning cnn model that can predict if skin cancer is Melanoma.

## Business Objective

To build a CNN based model which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The solution analyses a repository which contains various images belonging to following diseases and analyses a dataset.

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Repository contains the jypter notebook and some useful insights about the deep learning cnn model that alerts dermatologists about Melanoma which accounts for 75% in skin cancer disease. 
- The solution analyses a dataset which contain images belonging to various diseases.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initial dataset has class imbalance where some of the dataset are proportionately high. With right data augmentation and class imbalance treatement, initial model which was overfit, perfromed better with accuracy more than 81% both on training and validatoin set.
- Class has least number of samples is 'seborrheic keratosis'
- Class "pigmented benign keratosis" dominate the data in presence

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.2.1, Tensor flow, Keras deep learning cnn module and google col-lab
- The project was developed on google coloab as it requires GPU to train deep learning model

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by upgrad online learning community https://www.upgrad.com/
- This project was based on linear regressioin module.


## Contact
Created by [@Pragya12358] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
