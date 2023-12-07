# Pest Recognition

This report aims to provide a comprehensive approach to leverage machine learning for agricultural pest detection using a dataset comprising 2,479 real images of five distinct types of agricultural pests: Ants, Bees, Grasshoppers, Moths, and Wasps. The primary objectives includes dataset exploration, development and evaluation of two deep learning models with different architectures, comparison their performance, results interpretation, and discussion of potential strategies for enhancing the models in real world.

The structure of the report includes Data Preprocessing, Predictive Modelling, and Experiments Report.

Data Preprocessing

Initial data exploration involves visualizing sample images to gain insights into the variety and characteristics of 5 classes of pests, which can inform model development. Then, the dataset will be split into 70% for training and 30% for testing.

Predictive Modelling

Two deep learning models - Convolutional Neural Networks (CNNs) - with different architectures will be developed for pest classification.

Model 1: 1 Convolution and 1 Pooling layer; 1 Flattening and 1 Dense layer; and 1 Output layer

Model 2: 2 Convolution and 2 Pooling layers; 1 Flattening and 1 Dense layer; and 1 Output layer

The developed models will be evaluted through metrics such accuracy, kappa, precision, recall, F1-score. The evaluation will help assess each model's effectiveness in accurately classifying the different types of agricultural pests.

Experiments Report

The results of model evaluation will be thoroughly analyzed of each iteration with different hyperparameters. This section will help identify true impact factors of each model, and therefore give more insights on how to improve their performance capability. Thus, potential approaches for improving the model performance will be discussed. These strategies include architecture adjustment, parameters fine-tuning, and data collection.

In summary, this project aims to apply CNN model to to address the critical issue of agricultural pest detection. By developing and evaluating deep learning models on a diverse dataset, the ultimate goal is contribute to more accurate and efficient pest management in agricultural settings, reducing crop damage and increasing agricultural productivity.
