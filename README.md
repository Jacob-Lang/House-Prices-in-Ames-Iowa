# House-Prices-in-Ames--Iowa
 
 A full ML data science work flow. 
 
 In this project I go through a full ML workflow. From obtaining data, data exploration, pre-processing, model selection, hyperparameter tuning, model training and finally model submission.
 
 For this purpose I am using the data from a Kaggle competition to predict the sales price of houses given a list of features. This is a supervised learning regression problem. 
 
 In *House Prices.ipynb* I do the data exploration, some pre-processing, try out different models and use gridsearch cross-validation to tunne hyperparameters. 
 
 In *Pipeline.ipynb* I use sklearn's Pipeline to piece together the pre-processing and model training. I fine tune some of the pre-processing and again use gridsearch. I then use the model to predict the sales price on Kaggle's test set and submit to Kaggle. 
 
 My main purpose is not to get the best score necessarily but to practice a full ML workflow. 
 
 After an initial submission I found that my Kaggle position move forward ~400 places by introducing a scaling on the Sale Price label and fine tuning the hyperparameters of the regression model. 

