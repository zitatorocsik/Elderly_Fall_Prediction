# Elderly_Fall_Prediction

This project aims to develop and evaluate models that can predict and detect falls among the elderly, we will be using two models to try to accurately predict whether or not a person will fall based on 6 features.

The dataset we will be using is the ["Elderly Fall Prediction and Detection"](https://www.kaggle.com/datasets/laavanya/elderly-fall-prediction-and-detection/data) available on Kaggle. The dataset contains sensor data from a wearable called 'cStick' or calm stick collected from elderly participants which has the ability to not only detect falls but also predict the incident of the fall. It monitors the surroundings and warns the user if a previous fall was detected at a specific location, it then updates the location and its surroundings to the user. Based on the changes in the observed parameters, a fall decision (prediction, warning, or detection) is determined with an accuracy of around 95%.

The dataset has the following features:

['Distance', 'Pressure', 'HRV', 'Sugar level', 'SpO2', 'Accelerometer','Decision']

Decision is the label (the result) where the following values and corresponding meaning are used
{0:'No Fall detected',1:'Slip detected',2:'Definite fall'}
The dataset has 2039 instances. 

We will be using a supervised model: Random Forest Classifier and an Unsupervised model: Kmeans Clustering to fit this data set. 
