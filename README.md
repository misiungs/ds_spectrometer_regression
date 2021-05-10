# Spectrometer: regression
Data science project about regression of spectrometer data.

<img src="https://github.com/misiungs/readme_images/blob/master/spectrometer.jpg?raw=true" alt="drawing" width="500"/>

# Problem
For project purposes a dataset has been provided which consists of samples taken from spectrometer.
Each data point consists of 680 spectrometer readings and corresponding 'y' value.
The dependent variable may be seen as for example protein size and spectrometer data could be a corresponding milk sample.
The goal is to build a model which will predict 'y' based only on spectrometer measurements.

# Approach
First data exploration is performed.
For that PCA and t-SNE algorithms are used.
PCA is also applied to reduce the design space of a dataset to the most improtant components.
Reduced components are used for regression.
Various algorithms are applied and finally an ensamble approaches with Stacking Regressor for various models combinations have been done.

# Conclusions
Application of above algorithms allowed for accurate predictions of 'y' value.
The most satisfying results have been obtained for Support Vector Regression and Stacking Regressor methods.
