# Hydrate
This github page consist of the Machine Learning code that compares the six algorithms (Random Forest, Multilayer Perceptron, Polynomial Regression, Polynomial Regression with Ridge Regularization and K-Nearest Neighbors) that we use to estimate P-wave velocity and bulk density in near-seafloor sediments.
Training data and Validation data for the two Walker Ridge Holes WR313-G and WR313-H can be used from the files in .csv format for Vp Resistivity Case 1, Vp Resistivity Case 2 and Rhob Resistivity Case 1.
Also, there are 3 files that can be used for K-fold cross validation and are named using the suffix _K_fold_CV.
All the files are linked to the code and it can be executed to generate the output predicted Vp and RHOB corresponding to each Case using different algorithms.


To run the code, pick the well WR313-G or WR313-H to be used for validation, pick the variable to predict and also pick the Resistivity Case 1 or 2. For predicting RHOB, there is not Resistivity Case 2. Then, run Metrics, Data acquisition, Training and Validation Data, Normalizing the inputs. Then, go to the desired Machine Learning (ML) model and execute the code to generate the accuracy and error metrics and then plot the predicted variable vs the original variable to see the fit.
