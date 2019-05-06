# High-frequency-credit-rating-predict

This project is trying to use daily mraket data to predict companies' credit rating. The daily market data includes 
stock price and CDS spread. 

First, convert stock price and CDS spread to rating ralated features: default probability, distance to default, distance
to capital and default indicator by credit spread. Also interpolate quaterly data to calculate z-score. 

Then use the features mentioned to predict rating by mechine learning alforithmns like adaBoost, Boosting Tree, and upsampling
methods like SMOTE. 

The overall result for prediction by adaboost is over 80% for precision and over 90% for accuracy.

