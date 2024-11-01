# 🚕  Uber-Data-Analysis

### 🛣️  Objective:
To analyze and predict the 'Price' label using exploratory data analytics and various machine learning models, comparing their accuracy to identify the best performer.

### 🔧 DataSet:
For this project we are taken the dataset from kaggle in which there are 57 columns and approx 6 lakh rows and the file is in csv format. you can view or download the dataset through this link: https://www.kaggle.com/brllrb/uber-and-lyft-dataset-boston-ma

### 🛞 Application of this Project:
We use machine learning algorithms to predict the price of Uber, so that it is easy for the company to do analysis on price based on certain features.

### 🚦 Conclusion:
Before working on features first we need to know about the data insights which we get to know by EDA. Apart from that, we visualize the data by drawing various plots, due to which we understand that we don’t have any data for taxi’s price, also the price variations of other cabs and different types of weather. Other value count plots show the type and amount of data the dataset has. After this, we convert all categorical values into continuous data type and fill price Nan by the median of other values.With the help of corelation matrix, the features were selected.
We apply four different models on our remaining dataset among which Decision Tree, Random Forest, and Gradient Boosting Regressor prove best with 96%+ accuracy on training for our model. This means the predictive power of all these three algorithms in this dataset with the chosen features is very high but in the end, we go with random forest because it does not prone to overfitting and design a function with the help of the same model to predict the price.

## 🅿️ Prerequisites
- Python Project
- Jupiter notebook
- Git Hub link- https://github.com/mirajkarsneha/uber-project
- Presentation link - https://docs.google.com/presentation/d/14FPtcpx2nR6AO2dlCeyuLjcAXrkrNHnVbeFg5t2cjP8/edit#slide=id.g310b7b065ac_6_6

## ⛽ Data Preparation
- Column and null value dropping
- Correlation matrix plot
- Normalization & Feature Selection
- Modeling


## Project Structure
This is a python machine learning has below mentioned files.
- main.ipnyb - Which has all the logic written for the predicting price for different modles
- README.md - Describes what the project is, how it is structured and which model are used.
- data_cleaning.ipynb - How the data is being cleand based based on selected feature and target
