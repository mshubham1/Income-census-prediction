
# Income Price Prediction

To build a classification methodology to determineto whether a person’s income is above 50k or below 50k using various features like age, education, and occupation. 
## Table Content ✏️
* Demo
* Overview
* Dataset
* Installation
* Deployment
* Documentation
* Technology Used
* Motivation
* Conclusion
* Contribution
## Demo

![Income Predictor](https://user-images.githubusercontent.com/47842305/142749840-4bc29388-35b4-4e97-acbf-b0e71a02b94a.gif)


## Overview  📜
We will predict whether the person's income is above 50K or  below 50k using various features like age, education, and occupation. 
The application is a web app which is developed in Flask Framework.

>Read more about it at [Blogpost.](https://medium.com/@shubhammourya2014/census-income-prediction-f08ee9e4720d)

## Dataset  
The dataset we are going to use is the Adult census income dataset from Kaggle which contains about 32561 rows and 15 features that can be downloaded here
>Dataset link: https://www.kaggle.com/uciml/adult-census-income

## Installations  🗄️
The Code is written in Python 3.8 If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:


First you need to create a virtual conda enviornment.

```bash
  conda create -n myenv python=3.6
  pip install -r requirements.txt
```

## Deployment

> AWS Deployment Link: http://ec2-18-219-219-167.us-east-2.compute.amazonaws.com:8080/
```javascript
├── data
│   ├──incomedata.csv
├── log_file
│   ├── log_data.log
│   ├── logger.py
├── static
│   ├── image
│   ├── ├── img.jpg
├── templates
│   ├── database.html
│   ├── index.html
├── Money_Laundering_EDA.ipynb
├── XGB_Classifier.pkl
├── Procfile
├── EDA.ipynb
├── app.py
├── model_rf.pkl
├── requirements.txt
├── runtime.txt
├── README.md

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
