# Titanic-Machine-Learning-from-Disaster
This repository contains a machine learning project for predicting survival of passengers who travelled on Titanic Ship in 1912.

# Problem Description-
This project highlights my approach to the introductory machine learning competition on Kaggle website- Titanic: Machine Learning from Disaster [1].

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

This project analyses which people were likely to survive. In particular, tools of machine learning have been used to predict which passengers survived the tragedy.

# Project Description
This project has been made in Python v3.4. It uses various data processing, visualisation and machine learning packages such as numpy, pandas, matplotlib, scikit-learn etc. which should be installed if the code is run on a local machine.

The project uses a 5 step process (general procedure) for it's predicting task which is as follows [2]: 

  1) Perform a statistical analysis of the data and look over it's characteristics such as data type of columns, number of instances, correlation of each attribute with the output variable, finding mean and other information about data, correlation matrix etc.

  2) After performing statistical analysis, do a visual analysis by plotting the data. Do analyse the scatter_matrix, plot box plots etc. so as to know which attributes are relevant and which are not. Remove irrelevant attributes from the dataset for further analysis.

  3) Make a list of all machine learning algorithms that can give good prediction results and spot check each one of them (apply each one of them on the dataset) to find which one is better for prediction. Use k-fold cross validation to calculate performance characteristics of each of the learners (accuracy, precision, recall, area under ROC curve etc.).

  4) Take some of the good performing algorithms and perform a grid search/ randomised search over it's hyperparameters to find the optimal hyperparameters for the prediction task. Ensure that the optimal hyperparameters do not overfit the data, by performing k-fold cross validations on learners using these tuned hyperparametes as well.

  5) Use an ensemble or Voting Classifier on the above selected algorithms to achieve better performance or use any one of the above algorithm directly to perform predictions.

Keep iterating over the above steps again and again and tune them according to the need so as to achieve better performance.

# File Description

titanic_predictor - contains python code for predicting survival.

my_solution.csv - contains sample output file generated from algorithm.

train.csv- contains training data

test.csv - contains testing data for making predictions

readme.md - for guide to this project.

# Algorithm Performance
The procedure mentioned above in Project Description was successful in yielding decent results. The procedure had an accuracy of 81.34% on unseen validation set in this binary classification problem, which ranked 424 out of total 6613 contestants as of now [3] (top 7%)

Note - The results will keep changing over time as the competition is still ongoing.

# References
[1] Titanic: Machine Learning from Disaster (https://www.kaggle.com/c/titanic)

[2] Applied Machine Learning Process (http://machinelearningmastery.com/process-for-working-through-machine-learning-problems/)

[3] Titanic: Machine Learning from Disaster Leaderboard (https://www.kaggle.com/c/titanic/leaderboard)
