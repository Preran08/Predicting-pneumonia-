# Predicting-pneumonia-
Using Deep learning models to predict whether a person has pneumonia or not
Predicting Pneumonia from X-ray images using CNN and Keras
Problem
Detecting penumonia from X-ray images
Its a binary classification problem. The two classes are Normal and Pneumonia.
Normal Patients X-ray images
normal


Pneumonia effected X-ray images
disease

Source of Data
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal).
There are 5,863 X-Ray images (JPEG) and 2 categories as '1' indicates to Pneumonia and '0' to Normal. labels
Results
VGG16
vgg16

ResNet50
resnet

InceptionV3
inceptionv3

InceptionResNetV2
incepresnet

Xception
xception

results

VGG16 works best among all models with accuracy of 88.89%
