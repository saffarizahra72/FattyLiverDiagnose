# FattyLiverDiagnose
Fatty Liver Diagnose using AlexNet for Ultrasound Images

This is a tensorflow implementation for method provided in
"Fatty Liver Diagnose using AlexNet for Ultrasound Images" (under review)

To run our model follow the below steps:

1- To prepare the dataset, download it from the following and then run "Preparing.m"

2- Run "mainResNet.py" for the training model using ResNet-18. The best model will be saved in the folder "ResNetModels"

3- Run "ExatrctResNetFeatures.py" for extracting ResNet features. This code loads the best model from folder "ResNetModels" (in step 1) and then extracts train and test features in a specific layer number. Features will be saved in the folder "ResNetFeatures"

4- Run "RegResCapsNet.py" aiming signatures classification. This file used features of step 2 (which are saved in folder "ResNetFeatures") as input data.






