# FULLY AUTOMATWED MULTI-LABEL CLASSIFICATION OF RENAL ULTRASOUND IMAGES THROUGH DEEP CONVOLUTIONAL NEURAL NETWORKS
This project provides a means to produce labels by extracting text information embedded on 2D ultrasound images and performs multi-label classification tasks to predict both organ sites and anatomical planes of the ultrasound images. 
* * *
## Model Descriptions:
We build two CNN models, one simple CNN model as a baseline model and another CNN model with residual learning method with bottleneck structures. Also, we use tranfer learning to use pre-trained VGG16 and RestNet18 models.

All these models are trained on 2D ultrasound images and predict the images' organ site and anatomical plane.
## Requirements:
Python version 3.7.10 and Pytorch version 1.8.1 with CUDA version of 11.2 are required for the codes used in this study.
## Data preprocessing:
*Text_Extration.ipynb

*UPenn_data_toCSV.ipynb
## Training, validation, and testing:
*UPenn_CNN.ipynb

*UPenn_Bottleneck.ipynb

*UPenn_Transfer_Learning_VGG.ipynb

*UPenn_Transfer_Learning_Resnet.ipynb
## Results comparisons:
*UPenn_Final_graphs.ipynb
*UPenn_ResNet18_CAM.ipynb
