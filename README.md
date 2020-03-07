# Multiclass Dog Breed Classification

This notebook builds a multiclass image classifier using TensorFlow 2.0 and TensorFlow Hub.
## Problem

Identifying the breed of a dog given an image of a dog.
## Data

The data is from Kaggle's dog breed identification competetion.

https://www.kaggle.com/c/dog-breed-identification/data
## Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation
## Features

Information of the data:

* We have images(unstructured data) so it is best to use deep learning/transfer learning.

* There are 120 breeds of dogs i.e 120 different classes.

* There are around 10,000 images in the training and test sets.
    
![Dog Breeds Data](https://github.com/navendu-pottekkat/dog-eyes/blob/master/data.png)
    
## Results

The following image shows some of the predictions made by the model and its prediction probabilities(These predictions were made after training the model with 10% of the training data).

Score in Kaggle after evaluating the test data: 0.89228

![Result- Prediction probabilities](https://github.com/navendu-pottekkat/dog-eyes/blob/master/predictions.png)
