<center><h1> Predicting Invasive Tree Species </h1>
  
<br>

<center><h3> Abstract </h3></center>
  
  The purpose of this project is to build a machine learning model that can predict whether a tree species is invasive given the elevation, slope and aspect of land, soil information, location relative to the sun, water, roads, and wildfire sites. Identifying, containing, and preventing invasive tree species can reduce the harmful affects that these species have on their surrounding ecosystems, and even human lives. 

  Machine learning models are used to predict the answers to countless problems in our daily lives, such as which Instagram ads are most likely to interest you, what your next Netflix show should be, and auto-correct in your messaging app. Using a Random Forest machine learning model with a carefully tuned hyperparameter (n_estimators = 4360), we have the ability to predict with over 90% accuracy whether an tree species is invasive.

  To identify the best machine learning model to predict invasive tree species, I performed a grid search over 709 fits. Random Forest consistently out-performed Support Machine Vector (SVM) and Multi-layer perceptron (MLP) models by about 3% on average. Therefore, a Random Forest model with carefully tuned hyperparameters is the best machine learning model to use to predict invasive tree species.

<br> 

<center><h3> Motivation </h3>
<h4> Invasive Trees Threaten Ecosystems, Agriculture, and Human Health</center>

  According to the [Invasive Plant Atlas](https://www.invasiveplantatlas.org/trees.html) of the United States, an invasive species is one that is well outside of its known natural range. There are nearly 250 invasive tree species invading forests all over the U.S. due to human activity. These unwanted neighbors pose a threat to their surrounding ecosystem and could even harm agriculture and human health. We must do our part to recognize invasive tree species, and reduce their spread. 
  
<br>

<center><h3> Problem Statement </h3>
    <h4> Build a Model that Predicts Invasive Tree Species </h4></center>

  My model will predict whether a tree species is invasive or not given the features listed below (elevation, aspect, slope, soil characteristics, etc).
