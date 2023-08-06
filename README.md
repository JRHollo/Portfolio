# Portfolio
Portfolio of data science projects. Each headline below references the subfolder of and provides a breif description for the project.


## A/B Testing
This project is a quick mock-up to demonstrate how to perform A/B Testing. The dataset is a [Kaggle Dataset](https://www.kaggle.com/datasets/zhangluyuan/ab-testing) of an A/B Test. 


## AbsenteePredictions
This project was to create a model to predict if an absence was to be extended or not.  Extended, in terms of the target, was for a period of 3 or more hours.  Logistic regression was used as the modeling method. This folder contains the production ready distribution, which includes the pickle files for the custom scaler, model, and the class module to call preprocessing, scaling, model predictions, and wrting outputs.


## K_Means_Iris_dataset
This project was an attempt to apply K-Means clustering to the Iris dataset to identify the number of species. In this attempt, I split the data into two datasets (Iris-dataset.csv, Iris_with_answers.csv). I performed the clustering on the iris-dataset.csv, which excluded the species variable, and compared back to the Iris-with-answers.csv. Turns out that k-means clustering wasn't a good fit for identifying species as the k-means algorithm clustered on sepal instead of petal attributes, but, in biology, species were derived more by petal attributes.


## Linear_Regression_Used_Car_Prices
This folder houses the [final code](https://github.com/JRHollo/Portfolio/blob/main/Linear_Regression_Used_Car_Prices/Linear%20Reg%20Contender.ipynb) and [datasource](https://github.com/JRHollo/Portfolio/blob/main/Linear_Regression_Used_Car_Prices/1.04.%20Real-life%20example.csv) used to build a multivariate linear regression model to predict used car prices. This project was a course assignment for the Data Science Bootcamp 2022 certification offered through Udemy. The Jupyter Notebook documents the goal of the project, the scope, and methodology employed to solve the issue.
