# Predicting-solubility-LogS-using-LazyPredict-Random-Forest-and-Gradient-Boosting-Regressor-


In this project, I predicted LogS values from the SMILES of the molecules. I first used LazyPredict to quickly scan through different ML algorithms and to know which ones are the best models. From Lazy predict, I found out that Gradient Boosting Regressor and Random Forest Regressor are the best performing algorithms for this data set. So I use these two and optimise their n_estimators. I then was able to get about 91% as the best accuracy for these two models. Finally, I find that LogP is the most important feature for this prediction. 


## Acknowledgement
This idea was inspired by the Data Professor tutorial and Pat Walter's lecture in RSC CICAG.
