
# Pneumonia and Covid19 classification

The main aim of this project is to find out either  the respective
person's lungs are infected with Covid19, Pneumonia or Healthy lungs.

The data set is availabe in the Kaggle, in order to perform the 
classification with more accurate results, The Transfer learning 
approach has been used with InceptionV3 which is pre-trained with 
the Imagenet weights. Softmax function is used in the final layera
as we are using the model for multi-class classification. Later 
model is compiled using the loss function Categorical-cross entropy
and Adam optimizer.

Data-set link: 

https://www.kaggle.com/pranavraikokte/covid19-image-dataset

## Packages used

- Tensorflow
- Numpy 
- Matplotlib
- Glob

## Dataset count

| Test Data   |Count | Train data  | Count   | Total   | 
| ------------- | ------------- |------------- |------------- |------------- |
| Pneumonia   | 20  | Pneumonia  | 70  | 90  |
| Normal  | 20  | Normal  | 70  | 90|
| Covid19  | 26  | Covid19  | 111  | 137  |
| Total   |66 | Total  |   251 | 317   | 

# Total no of Parameters
| Parameters | No of parameters|
| ----------| ------------------|
|Trainable Parameters | 153, 603|
|Non - Trainable Prameters| 21,802,784|
|Total Parameters | 21,956,387|

## Accuracy
|Accuracy | 97%|
|---------------|-----------|


## InceptionV3 :

Inception V3 by Google is the 3rd version in a series of Deep Learning Convolutional Architectures. Inception V3 was trained using a dataset of 1,000 classes (See the list of classes here) from the original ImageNet dataset which was trained with over 1 million training images, the Tensorflow version has 1,001 classes which is due to an additional "background' class not used in the original ImageNet. Inception V3 was trained for the ImageNet Large Visual Recognition Challenge where it was a first runner up.

## Architecture 
![This is an image](https://www.apriorit.com/images/articles/applying_inception_v3/figure-1.jpg)

