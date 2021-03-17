# Predicting Chronic Kidney Disease

A paper written for CS6140 - Machine Learning final project in Fall of 2020. The goal of the project was to use machine learning techniques on data from the Open Source MIMIC-III and Massachusetts General Bringham Electronic Healthcare records to predict chronic kidney disease in patients, specifically their eGFR value. 

The project was a comparative study of machine learning techniques including Random Forests, Linear Regression with L2 regularization, and a variety of Neural Networks. An exhaustive grid search was coded in order to tune hyper parameters in each technique. The end results showed that Neural Networks slightly outperformed the other methods, producing a mean absolute error of 13 on the eGFR scale of 0-100.

The following tools were used:
 - Python
 - Tensorflow
 - Scikitlearn
 - Juptyer Notebooks