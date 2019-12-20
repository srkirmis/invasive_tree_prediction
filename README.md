<center><h1> Predicting Invasive Tree Species </h1>

<center><h3> ~~~~~~~~~~ ABSTRACT ~~~~~~~~~~ </h3>
  
The purpose of this project is to build a machine learning model that can predict whether a tree species is invasive given the elevation, slope and aspect of land, soil information, location relative to the sun, water, roads, and wildfire sites. Identifying, containing, and preventing invasive tree species can reduce the harmful affects that these species have on their surrounding ecosystems, and even human lives. 

Machine learning models are used to predict the answers to countless problems in our daily lives, such as which Instagram ads are most likely to interest you, what your next Netflix show should be, and auto-correct in your messaging app. Using a Random Forest machine learning model with a carefully tuned hyperparameter (n_estimators = 4360), we have the ability to predict with over 90% accuracy whether an tree species is invasive.

To identify the best machine learning model to predict invasive tree species, I performed a grid search over 709 fits. Random Forest consistently out-performed Support Machine Vector (SVM) and Multi-layer perceptron (MLP) models by about 3% on average. Therefore, a Random Forest model with carefully tuned hyperparameters is the best machine learning model to use to predict invasive tree species.
