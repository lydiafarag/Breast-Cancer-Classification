# Breast-Cancer-Classification
Using python and Keras, I am building a classifier that will train on 80% of a breast cancer histology image dataset (IDC dataset). 10% is retained for data validation (ie., error checking our machine learning model). I defined a convolutional neural network that is trained on the images and then I derived a confusion matrix to asses the model's efficacy.

**A background on Breast Cancer Histology**

Breast cancer is one of the leading causes of death for women in North America, but early detection prior to cancer metastasis saves lives. 

Invasive Ductal Carcinoma is a type of breast cancer that develops in milk ducts, breaks the basement membrane of the cell, and invades the fibroud or fatty breat tissue outside of the duct. It is the most common form of breast cancer. 

The dataset in use is from Kaggle and it holds over 200 000 patches extracted from 162 slide images of breast cancer speciments. Of all of these, approximately, 70% were benign and 30% were malignant. 


This dataset is public domain and accesible at https://www.kaggle.com/paultimothymooney/breast-histopathology-images/
