# Shopping-Trend

# Project Overview
This project analyzes supermarket sales data to extract meaningful insights into customer purchasing patterns, sales trends, and product performance. The analysis was conducted using Python, leveraging its powerful data processing and visualization capabilities to deliver comprehensive insights

## Dataset
The dataset used for this analysis contains detailed sales transactions from a supermarket, including information on:

Product details (category, sub-category, and name)

Sales and profit data

Customer demographics

Transaction details (date, location, and sales amount)

Data preprocessing involved handling missing values, correcting inconsistent data formats, and ensuring accuracy for analysis. The data was then organized to facilitate in-depth exploration and visualization

## Library Used
1) Numpy
2) Pandas
3) Matplotlib
4) Seaborn
5) Sklearn

## Analysis Techniques
### Step 1: Importing the Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

### Step 2: Importing the Dataset
shop=pd.read_csv('shopping_trends.csv')

## Screenshot Of the Analysis
plotting the integer columns

shop.hist(bins = 28, figsize=(15, 10), color ='olive')

plt.show()

![Image](https://github.com/user-attachments/assets/f090e02b-644d-4055-917e-18125b1de087)
