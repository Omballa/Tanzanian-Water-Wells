# Tanzanian Water Wells Analysis
Author: William Brandon Omballa

## Overview
![Tanzanian Water Wells](images/wells.jpg)

The stakeholder will be the Tanzanian Government. The purpose of this project is to provide the Tanzanian Government with valuable insights on well status across the country to help in the allocation of resources, as well as a predictive model that can be used to make recommendations on wells that need to be repaired or will soon not be functional.

## Business and Data Understanding
The Government of Tanzania would like to ensure that all it's citizens have access to clean and adequate water.

Using the data collected by Taarifa, I would like to determine the key features that can be used to predict a well's condition hence make appropriate recommendations.

## Data & Methodology
The data used is collected by an organization called Taarifa. The scope of this project is to create a binary classification model.

However, the target column has 3 values: 
1. Functional
2. Functional needs repair
3. Non functional

To convert the data to binary form. We grouped Functional Needs repair and Non functional together to create two classes. Functional and Non Functional.

I believe that this approach is good as Functional Needs Repair wells will be flasgged as Non functional and this can aid in quick repairs to be done before the affected region has lost water completely. Also our model predicted it better as compared to making Functional Needs repair to the Functional class.

## Exploratory Data Analysis (EDA)
Here I would like to explore the dataset more so as to get an general understanding.


Modeling
Evaluation
Conclusion