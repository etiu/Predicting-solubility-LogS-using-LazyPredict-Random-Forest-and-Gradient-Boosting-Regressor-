# Predicting-solubility-LogS-using-LazyPredict-Random-Forest-and-Gradient-Boosting-Regressor-


In this project, I predicted LogS values from the SMILES of the molecules. I used MW, number of H bond donors, number of H bond acceptors, the polar surface area, the number of aromatic rings, and logP as independent variables to predict the Log S. I first used LazyPredict to quickly scan through different ML algorithms and to know which ones are the best models for this dataset. From Lazy predict, I found out that Gradient Boosting Regressor and Random Forest Regressor are the best performing algorithms for this data set, with the biggest adjusted R2 scores and smallest RMSE. So I use these two and optimise their n_estimators. I then was able to get about 91% as the best accuracy for these two models. Finally, I find that LogP is the most important feature for this prediction. 


## Data set
The data set was obtained from the original paper by John Delaney. J. Chem. Inf. Comput. Sci. 2004, 44, 3, 1000–1005.

## Acknowledgement
This idea was inspired by the Data Professor tutorial and Pat Walter's lecture in RSC CICAG.
