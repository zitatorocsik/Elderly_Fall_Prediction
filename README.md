# Elderly_Fall_Prediction
 
In this project, we will be using two models to try to accurately predict whether or not a person will fall based on 6 features.

The dataset we will be using is the "Elderly Fall Prediction and Detection" available on Kaggle.
The dataset has the following features:

['Distance', 'Pressure', 'HRV', 'Sugar level', 'SpO2', 'Accelerometer','Decision']

Decision is the label (the result) where the following values and corresponding meaning are used
{0:'No Fall detected',1:'Slip detected',2:'Definite fall'}
The dataset has 2039 instances. 

We will be using a supervised model: Random Forest Classifier and an Unsupervised model: Kmeans Clustering to fit this data set. 
