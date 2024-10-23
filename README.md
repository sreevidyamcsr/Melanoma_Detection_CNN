# Melanoma Detection using Convolutional Neural Networks
> This project involves building a multiclass classification model using a custom convolutional neural network (CNN) in TensorFlow to detect melanoma and other skin diseases. Melanoma, a deadly type of skin cancer, accounts for 75% of skin cancer deaths, making early detection crucial. The goal is to develop a solution that can evaluate images and assist dermatologists in diagnosing melanoma, thereby reducing manual effort.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background: This project focuses on utilizing deep learning techniques, specifically CNNs, to classify skin disease images. The ability to accurately detect melanoma has significant implications for early intervention and treatment.

- Business Problem: Early detection of melanoma can save lives and reduce the healthcare burden. This model aims to assist dermatologists in making quicker and more accurate diagnoses based on image analysis.

- Dataset: The dataset consists of 2357 images of malignant and benign skin diseases, sourced from the International Skin Imaging Collaboration (ISIC). The dataset includes various skin conditions, such as:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model Performance: The custom CNN model was trained to classify images into 9 categories, with observations made regarding overfitting and underfitting after training on the initial dataset.

- Data Augmentation: Implementing data augmentation strategies improved model robustness and reduced overfitting, leading to better generalization on unseen data.

- Class Imbalance Handling: The class distribution was examined, revealing certain classes with fewer samples. Techniques were applied using the Augmentor library to rectify class imbalances, resulting in improved model accuracy.

- Final Model Training: The final model, trained on rectified data for approximately 30 epochs, demonstrated enhanced classification performance, with reduced evidence of previous overfitting or underfitting issues.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.8
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- Augmentor
- scikit-learn
