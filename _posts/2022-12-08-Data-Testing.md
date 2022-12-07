---
layout: post
title: "Data Testing"
author: "Ryshant Padarath & Sherlin Chand "
categories: facts
tags: [sample]
image: 567192A7-58DF-451D-BAE6-B6FF1E217D90.jpeg
---

1)Raw Data 

By selecting the forward kinematics as predictors and inverse kinematics as response, the team trained the data accordingly. 
The first step was to use to train the raw data and observe the results. The team utilized the first portion of the data to train with the data division of 70%, 15% and 15% as training set, validation set and test set. The training algorithm was Levenberg-Marquardt and the performance was determined by the mean squared error. 

2)Normalized Data

The dataset was normalized through the Matlab codes, the first and second portion was trained through the training algorithm Levenberg-Marquardt and the value for the mean squared error was observed.

3)PCA plus Normalized Data

Principle component analysis was used with the normalized dataset and was trained. This step is done so that the mean squared error is compared between raw data, normalized data and normalized with PCA. 

4)Data Testing 

Testing of the trained shallow neural network is an essential part of the project. This step is done to find the inverse kinematic solution and to observe how well the dataset has been trained to try to predict the inverse kinematics
