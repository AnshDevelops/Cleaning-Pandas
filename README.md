# Cleaning-Pandas

This repository contains a Jupyter Notebook that demonstrates the impact of data cleaning on the performance (accuracy) of AlexNet in a multi-class image classification project dealing with images of pandas.
The purpose of this project is to showcase the importance of data preprocessing and cleaning in improving the accuracy of machine learning models.

View the notebook on Kaggle: [Cleaning-Pandas-Kaggle-Notebook](https://www.kaggle.com/code/soggyansh/cleaning-pandas/notebook)

## The Dataset

![image](https://github.com/AnshDevelops/Cleaning-Pandas/assets/152869575/0aeb6cfb-a9e9-4cf5-bb01-821c132b9075)

## Metrics before cleaning data

Model used: AlexNet
![image](https://github.com/AnshDevelops/Cleaning-Pandas/assets/152869575/29ec2f8f-e8fd-4d8a-bd93-26bd5e29400d)

Results: Accuracy = 95.6%

## Metrics after cleaning data
Fast.ai's ImageClassifierCleaner tool is used to clean the dataset.

Model used: AlexNet
![image](https://github.com/AnshDevelops/Cleaning-Pandas/assets/152869575/62ad912b-4c81-4950-8ffb-1a55324ebdda)

Results: Accuracy = 98.6%

## Prerequisites
To run the Jupyter Notebook locally, ensure that you have the following dependencies installed:

* Python (3.6 or higher)
* Jupyter Notebook
* PyTorch
* torchvision
* fastai

## Additional recommended requirements
Install the following if you want to use your local GPU:

* Nvidia Cuda (11.7 or higher)
* Nvidia CuDNN
