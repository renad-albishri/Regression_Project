# Diamonds Price Prediction

## Overview

Diamonds belonge to a unique class of product, In this project, we are going to work on a dataset that consists of information about the diamond's price, and other aspects such as Clarity, etc.
This project aimed to use a regression linear model on a diamonds dataset to predict the price.
The challenge that gives value to our project is web scraping by selenium and beautiful soup library

## Goals

- Which variables are significant in predicting the price of a diamonds
- Build a model to predict the diamonds price.
- Choose the model that give us the best predict.

## Methodology

1- Web scrapping the data 

2- EDA (clean and visualize the data

3- Build Regression Model

4- Prediction

## Diamonds Dataset 

The dataset used in this project was obtained by scraping data from  brilliant earth website that offers one of the largest collections of diamonds available for sale, website https://www.brilliantearth.com/

The dataset contains the prices and other attributes of almost 119,000 rows and 11 features. It's a great dataset for machine learning and working with data analysis and visualization.

After we cleaned the data, the rows became about 68,000 and 7 features.

### Dataset Columns :

- price : price in US dollars ( \\$450 - \\$145,210 )

- carat : weight of the diamond ( 0.25 - 10.54 )

- cut : quality of the cut ( Super Ideal, Very Good, Ideal, Good, Fair )

- color : diamond colour (I  ( worst ) , F, E, J, G, H, D ( best )) 

- clarity : a measurement of how clear the diamond is ( I1 (worst) ,SI2 ,SI1 ,VS2 ,VS1 ,VVS2 ,VVS1 ,IF (best))

- shape : diamonds shape (Round, Marquise, Princess, Heart, Emerald, Pear, Oval, Cushion, Radiant, Asscher)
       
- report : a diamond certificate (GIA, IGI, HRD, GCAL)

- LW ratio: length to width ratio.

- type : a type of dimonds ( natural, lab)


## Regression :



On this dataset we used different methods of regression :

- Linear Regression

- Polynominal Regression

- Lasso Regression

- Ridge Regression

- ElasticNet Regression

The best accuracy between these algorithms is 98.07 % with Polynominal Regression with degree 5.



## Tools

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Patsy
- Sklean
- LinearRegression
- Statsmodels.api
- BeautifulSoup
- Selenium webscraping


```python

```
