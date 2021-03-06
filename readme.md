
# Income Price Prediction

To build a classification methodology to determineto whether a personβs income is above 50k or below 50k using various features like age, education, and occupation. 
## Table Content βοΈ
* Overview
* Dataset
* Installation
* Deployment
* Documentation
* Technology Used
* Motivation
* Conclusion
* Contribution



## Overview  π
We will predict whether the person's income is above 50K or  below 50k using various features like age, education, and occupation. 
The application is a web app which is developed in Flask Framework.

>Read more about it at [Blogpost.](https://medium.com/@shubhammourya2014/census-income-prediction-f08ee9e4720d)

## Dataset  
The dataset we are going to use is the Adult census income dataset from Kaggle which contains about 32561 rows and 15 features that can be downloaded here
>Dataset link: https://www.kaggle.com/uciml/adult-census-income

## Installations  ποΈ
The Code is written in Python 3.8 If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:


First you need to create a virtual conda enviornment.

```bash
  conda create -n myenv python=3.6
  pip install -r requirements.txt
```
## Deployment
> AWS Deployment Link: http://ec2-18-219-219-167.us-east-2.compute.amazonaws.com:8080/

![Income Predictor](https://user-images.githubusercontent.com/47842305/142749840-4bc29388-35b4-4e97-acbf-b0e71a02b94a.gif)

## Directory


```javascript
βββ data
βΒ Β  βββincomedata.csv
βββ log_file
βΒ Β  βββ log_data.log
βΒ Β  βββ logger.py
βββ static
βΒ Β  βββ image
βΒ Β  βββ βββ img.jpg
βββ templates
β   βββ database.html
βΒ Β  βββ index.html
βββ Money_Laundering_EDA.ipynb
βββ XGB_Classifier.pkl
βββ Procfile
βββ EDA.ipynb
βββ app.py
βββ model_rf.pkl
βββ requirements.txt
βββ runtime.txt
βββ README.md

```
## Technologies Used

* Python
* FrontEnd: HTML & CSS
* Backend: Flask 

## Motivation

* Building such predictive models can help us better understand the population of a country as well as the various factors affecting the growth in the economy.
* Governments can understand such factors and improve upon them leading to the growth of the country.
## Conclusion
* In this project, we build various models like logistic regression, knn classifier, support vector classifier, decision tree classifier, random forest classifier and xgboost classifier.
* A hyperparameter tuned random forest classifier gives the highest accuracy score of 92.77 and f1 score of 93.08.
## Contributers
You can feel free to reach out me at shubhammourya2014@gmail.com

@Shubham Mourya
