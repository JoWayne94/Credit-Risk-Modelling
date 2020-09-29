# Credit-Risk-Modelling
This is an introductory project to credit risk during the author's internship at Maxis Communications (All work done in the summer of 2019). Due to cost considerations, the AI & Advanced Analytics team attempts to build an efficient tool for the Consumer Business department in order to easily and accurately assess the default risk of clients if offered a contract. Precisely, the main purpose of the project is to predict the creditworthiness of consumers by scoring them, thus it is a multi-classification problem. Unfortunately, Maxis client datasets are confidential thus cannot be made public. Hence a dataset from Kaggle is used, and can be found through this link:

https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset

The dataset consists of roughly 30,000 consumers characterized by 25 variables. The models implemented present an average predictive power (mean AUC around 0.717), but of course they were only example models of author's learning process. They are obtained by using logistic regression, random forest and neural network techniques. 

An individual report containing all technical details is included. Exploratory Data Analysis is performed on Default Credit Card of Taiwan Clients in 2005 (link above) to get familiar with the available data. ML theories are breifly discussed in the report. Data was processed before feeding to the models. Model results and limitations are also evaluated with performance detailed at the end.

Both scripts are written in Jupyter Notebook. UCI_Credit_Card.csv file is needed to run the EDA.ipynb file. This gives the credit_card.csv output, which is the file needed to run the Model Development.ipynb file.
