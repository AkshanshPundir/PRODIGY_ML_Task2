# PRODIGY_ML_Task2
Created a K-means clustering algorithm to group customers of a retail store based on their purchase history.

Link to the dataset : https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Introduction

Customer segmentation is a key practice in marketing, where customers are divided into groups based on common characteristics. This project uses the K-means clustering algorithm to segment customers based on their annual income and spending score. The objective is to understand different customer groups and tailor marketing strategies accordingly.

## Data

The dataset used for this project is `Mall_Customers.csv`, which contains the following columns:

- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousand dollars
- `Spending Score (1-100)`: Spending score assigned by the mall based on customer behavior and spending nature

## Installation

To run the code, you need to have Python installed along with the following libraries:

- pandas
- matplotlib
- scikit-learn

You can install the required libraries using pip:

```sh
pip install pandas matplotlib scikit-learn
