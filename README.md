# Melanoma Detection using CNN
> A deep learning project aimed at detecting melanoma, a type of skin cancer, from images using Convolutional Neural Networks (CNNs).

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project builds a custom CNN model to detect melanoma, a severe type of skin cancer responsible for the majority of skin cancer-related deaths.
- The objective is to aid dermatologists in detecting melanoma early by automating the analysis of skin lesion images.
- The dataset used comprises **6739 images** from the **International Skin Imaging Collaboration (ISIC)**, categorized into 9 classes:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion

## Conclusions
- The model achieved a **training accuracy of 90.10%** and a **validation accuracy of 87.81%**, demonstrating strong learning and generalization capabilities.
- The inclusion of data augmentation and dropout layers effectively mitigated overfitting.
- Mild overfitting was observed in later epochs, but validation performance remained strong.
- Further improvements could include advanced regularization techniques and testing on an external dataset.

## Technologies Used
- Python - version 3.8
- TensorFlow - version 2.9.1
- NumPy - version 1.22.4
- Pandas - version 1.4.3
- Matplotlib - version 3.5.2
- Augmentor - version 0.2.8

## Acknowledgements
- This project was inspired by the **International Skin Imaging Collaboration (ISIC)** dataset.
- References:
  - ISIC Dataset: [ISIC Archive](https://www.isic-archive.com)
  - Augmentor Documentation: [Augmentor Library](https://augmentor.readthedocs.io/en/master/)
- This project was guided by [upGrad and IIITB](https://www.upgrad.com/machine-learning-and-ai/).

## Contact
Created by [@anilchaganti007] - feel free to contact me for collaboration or queries!
