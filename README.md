# Retail Customer Segmentation Using Unsupervised Machine Learning
Data Source: Kagglehub
## Project Overview

This project analyses retail transaction data to identify distinct
customer segments based on purchasing behaviour.

## Objective

The objective of this project is to transform raw retail transaction
data into meaningful customer-level features and use unsupervised
machine learning to identify groups of customers with similar
characteristics.

## Data Preparation

The dataset was cleaned by:

- Handling missing values
- Converting Customer ID to string
- Addressing zero values in price and quantity
- Removing duplicate records
- Treating outliers

## Exploratory Data Analysis

Box plots, histograms, scatter plots and line plots were used to
investigate distributions, relationships and trends within the data.

## Feature Engineering

Two additional features were created:

- Customer Frequency
- Total Amount

## Modelling

The prepared features were rescaled before clustering.

K-Means clustering was applied to segment customers. Other
unsupervised learning approaches were also evaluated.

## Model Evaluation

The clustering solutions were evaluated using:

- Silhouette Score
- Calinski-Harabasz Index
- Davies-Bouldin Index

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
