This tutorial covers the following steps:

Import data into Unity Catalog
Visualize the data using Seaborn and matplotlib
Run a parallel hyperparameter search to train machine learning models on the dataset
Explore the results of the hyperparameter sweep with MLflow
Register the best performing model in MLflow
Apply the registered model to another dataset using a Spark UDF
Set up model serving for low-latency requests
In this example, you build a model to predict the quality of Portugese "Vinho Verde" wine based on the wine's physicochemical properties.

The example uses a dataset from the UCI Machine Learning Repository, presented in Modeling wine preferences by data mining from physicochemical properties [Cortez et al., 2009].
