
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

| Test Data              | count |  
| ----------------- | ----|
| covid test data  | 26  || covid train data  | 111  |
| Normal test data  | 20|| Normal train data  | 70|
| pneumonia test data  | 20|| pneumonia train data  | 70|
| Total test data   | 66|| Total train data   | 251|


| Accuracy | 97.21% |
| LOss     | 09.23% |
