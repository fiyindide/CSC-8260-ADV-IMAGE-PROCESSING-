# CSC-8260-ADV-IMAGE-PROCESSING
## Automated Rice Plant Disease Classification Using Image Processing and Machine Learning


#### Course: CSC 8260 (Course Project)

## Objective


The aim of this project is to implement a rice leaf disease classification system using transfer learning with two pretrained convolutional neural network architectures: ResNet50 and VGG16. The dataset consists of labeled images categorized into three classes: Bacterial Leaf Blight, Brown Spot, and Blast, with 1300 images per class. 

## Steps:
1. **Data preprocessing and augmentation**
2. **Dataset visualization and distribution analysis**
4. **Model Setup: Transfer Learning using ResNet50 and VGG16**
    - Load pretrained weights from ImageNet.
    - Freeze the convolutional base to retain learned features.
    - Add custom fully connected layers for classification (Dropout + Dense)
5. **Model Training**
6. **Model Evaluation**
6. **Analysis and Discussion**
