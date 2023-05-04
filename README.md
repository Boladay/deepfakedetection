# Artificial Image Detector CNN Model using DenseNet
----------------------------------------------
## Project Overview

For this project I created CNN Model using DenseNet. This model objective was to accuratly tell the difference between a deepfake image and a real image. For training puropses and to see the execution of the model, we used a image dataset which contained around 140,000 images, both real and fake. The dataset was split into Training, Testing and Validation. With Training containing around ≈70%, Testing ≈15% and Validation ≈15%. The model was shown to have an accuracy of around 95%. 


## Preperations

* I first **Explored** the dataset, this is to get a better understanding of the dataset before working on it.
* Secondly the dataset was **Cleaned** this is get rid of any duplicates or null values which may hinder the model.
* Finally i **Prepared** the dataset, this was done by splitting the dataset into Training, Testing and Validation.


## What does the model consist of?

* The model makes use of Keras ImageDataGenerator, this library allows us to transform flip, rescale, rotate, and transform the images within the dataset in variety of ways. This allows the dataset to train itself to recognize images that may not present themselves in a convenient manner, and therefore improve the recognizability of the CNN model.
* The DenseNet model itself consisted of denseblocks which are made up of convulution layers. Transition layers and pooling layers.
* Batch Normalization is then applied to ensure the model is not skewed, preventing overfitting.




