# Titanic-Machine-Learning-from-Disaster
This repository contains a machine learning project for predicting survival of passengers who traveled on Titanic Ship in 1912

# Problem Description-
This project highlights my approach to the introductory machine learning competetion on Kaggle website- Tiranic: Machine Learning from Disaster.

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

This project analyses which people were likely to survive. In particular tools of machine learning have been used to predict which passengers survived the tragedy.

# Project Description
This project has been made in Python v3.4. It uses various data processing, visualisation and machine learning packages such as numpy, pandas, matplotlib, scikit-learn etc. which should be installed if the code is to be ran on a local machine.

The project uses a 5 step process (general procedure) for it's predicting task which is as follows-

1). Take a look over the data and analyse it's characteristics such as data type of columns, number of instances, correlation of each attribute with th output variable, finding mean and other information about data, correlation matrix etc.

2). After performing statistical analysis, do a visual analysis by plotting the data. Do analyse the scatter_matrix, plot box plots etc. so as to know which attributes are relevant and which are not. Remove irrelevant attributes from the dataset for further analysis.

3). Make a list of all machine learning algorithms that can give good prediction results ans spot check each one of them (apply each one of them on the dataset) to find which one is better for prediction. Use k-fold cross validation to calculate performance characteristic of each of the learners (accuracy, precison, recall, area under ROC curve etc.).

4). Take some of the good performing algorithms and perform a grid search/ randomised search over it's hyperparameters to find the optimal parameters for the prediction task. Do ensure that the optimal parameters do not overfit the data, by performing k-fold cross validations on learners using these tuned hyperparametes as well.

5). Use an ensemble or Voting Classifier on the above selected algorithms to achieve better performace or use any one of the above algorithm directly to perform predictions.

Keep iterating over the above steps again and again, tuning them according to the need so as to acheive better performance.


# File Description

titanic_predictor - contains python code for predicting survival.
my_solution - contains output file generated from algorithm.
train.csv- contains training data
test.csv - contains testing data for making predictions
readme.md - for guide to this project.

# References
1) Titanic: Machine Learning from Disaster (https://www.kaggle.com/c/titanic)
2) Applied Machine Learning Process (http://machinelearningmastery.com/process-for-working-through-machine-learning-problems/)
