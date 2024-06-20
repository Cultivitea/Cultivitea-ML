# Cultivitea-ML
## Introduction
This repository contains Machine Learning model used by Cultivitea application and the Google Colab used for training and generating the model.
## Description
In building model, we used TensorFlow as our framework for deep learning model. We used MobileNet as the pre trained model. For the deployment, we tried TF Lite and TF.js but the one that we used in Cultivitea was the model that deployed by TF.js.
## Datasets
The dataset that is used by Cultivitea is from Kaggle [Tea_Leaf_Disease](https://www.kaggle.com/datasets/saikatdatta1994/tea-leaf-disease/data). The dataset consists of 6 labels, which are Algal Spot, Brown Blight, Gray Blight, Healthy, Helopeltis, and Red Spot. Except Gray Blight which has 867 images, the other labels have 1000 images so in total there are 5867 images used.