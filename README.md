# Python for Data Analysis - Final Project Report

**Author: Maxence Ravau-Gaëlle Rigaud**

## 0. Introduction
- Imported dataset: "online_shoppers_intentions" (August 2018)
- Dataset description: 12,330 rows, 18 variables
- Target variable: "Revenue" (boolean)
- Libraries used: Pandas, Matplotlib.pyplot, Numpy, Seaborn

## 1. Data Visualization
### 1.1 Number of sales
- Analyzed sales made each month
- October had the highest number of sales

### 1.2 Never Purchased Products
- Identified products never bought by customers
- Created two sub-datasets: "allSales" and "noSale"
- Verified that purchased products are a subset of all products
- Obtained a list of 86 products never purchased

### 1.3 Most Consulted and Purchased Products
- Identified the most consulted and purchased products
- Top 10 most consulted products were different from the most purchased products
- Most consulted products were not highly sold

### 1.4 Pre-Purchase Behavior
- Explored the relation between time spent on a product page and number of sales
- Explored the relation between number of pages visited and Revenue
- Examined the correlation between visitor type and Revenue

### 1.5 Seasonal Behavior
- Analyzed consumer behavior on weekends and special days
- More sales on business days and special days

### 1.6 Correlation between all the variables
- Constructed a correlation matrix
- Identified significant correlations between variables
- PagesValues had the highest positive correlation with Revenue

## 2. Supervised Learning
### 2.1 Preparation of the dataset
- Split the dataset into training and testing sets
- Converted qualitative data to quantitative data

### 2.2 Principal Components Analysis
- Performed PCA on the training set
- Visualized data in two dimensions
- Found that the two principal components explained only 36% of the variance

### 2.3 Find the best parameters of a model
- Utilized GridSearchCV to find the best parameters for each model

### 2.4 Test different models
- Tested logistic regression, linear discriminant analysis, quadratic discriminant analysis, decision tree classifier, and K-neighbors classifier models
- Logistic regression achieved the highest accuracy of 88.52%

## Conclusion
- Explored and visualized the dataset to gain insights into customer behavior
- Built classification models to predict sales
- Logistic regression model achieved the highest accuracy of 88.52%
