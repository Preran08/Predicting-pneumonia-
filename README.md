# Predicting-pneumonia-
Using Deep learning models to predict whether a person has pneumonia or not
Predicting Pneumonia from X-ray images using CNN and Keras
Problem
Detecting penumonia from X-ray images
Its a binary classification problem. The two classes are Normal and Pneumonia.
## Normal Patients X-ray images

![1](https://user-images.githubusercontent.com/38466518/110576865-83d2ac00-812f-11eb-991b-4e5ac9a08d44.png)


## Pneumonia effected X-ray images


![2](https://user-images.githubusercontent.com/38466518/110576936-a82e8880-812f-11eb-99d9-4775490dc795.png)


## Source of Data
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal).
There are 5,863 X-Ray images (JPEG) and 2 categories as '1' indicates to Pneumonia and '0' to Normal. labels

![3](https://user-images.githubusercontent.com/38466518/110576940-a9f84c00-812f-11eb-8f35-9b12f217e446.png)

# Results
## VGG16


![4](https://user-images.githubusercontent.com/38466518/110576942-ab297900-812f-11eb-897b-a401dd120fcd.png)


## ResNet50


![5](https://user-images.githubusercontent.com/38466518/110576946-acf33c80-812f-11eb-8cf5-d6598fd8ecd8.png)


## InceptionV3


![6](https://user-images.githubusercontent.com/38466518/110576959-b1b7f080-812f-11eb-95b5-553670251e10.png)


## InceptionResNetV2


![7](https://user-images.githubusercontent.com/38466518/110576968-b2e91d80-812f-11eb-987d-dd37ec5428cb.png)


## Xception


![8](https://user-images.githubusercontent.com/38466518/110576972-b41a4a80-812f-11eb-84fc-47f8783a86fe.png)


## Results

![9](https://user-images.githubusercontent.com/38466518/110576975-b5e40e00-812f-11eb-8783-fd07c92206e3.png)


VGG16 works best among all models with accuracy of 88.89%
