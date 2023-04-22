# A Hybrid Method for Imputation of Missing Values using Optimized Fuzzy C-Means with Support Vector Regression and a Genetic Algorithm
This project is a hybrid method for imputing missing values in datasets using a combination of three different techniques: Optimized Fuzzy C-Means (OFCM), Support Vector Regression (SVR), and a Genetic Algorithm (GA).

## What is the purpose of this project?

The purpose of this project is to develop a more accurate and efficient method for imputing missing values in datasets. Missing values are a common problem in data analysis, and they can lead to inaccurate results and conclusions. This project aims to overcome this problem by using a hybrid approach that combines the strengths of three different techniques.

## How does the method work?

The method works by first using OFCM to cluster the data and identify patterns. The clusters are then used to train an SVR model to predict the missing values. Finally, a GA is used to optimize the parameters of the SVR model for maximum accuracy.
How to use the code?

The code is written in Python and can be run using a Python IDE such as PyCharm or Jupyter Notebook. The code requires the following libraries to be installed:

    numpy
    pandas
    sklearn
    skfuzzy
   
The main script is main.py, which takes a CSV file as input and outputs a new CSV file with the missing values imputed. The steps are

1. Import pandas, numpy, os, skfuzzy, time, copy, random
2. Two empty folders is given, copy the incomplete datasets in "Incomplete Datasets folder", and complete datasets in "Complete DataSets Folder"
3. Change in the value of the file which has to be run in main.py file, example main("Data_2_NN_5%.csv")
4. The datasets will be loaded automatically based on the input and missing value will be imputated.
5. The NRMS value, C, M, run time will be displayed at the end of execution.

## Conclusion
This project presents a hybrid method for imputing missing values in datasets that combines OFCM, SVR, and a GA. The method has been shown to be more accurate and efficient than traditional imputation techniques. The code is available for use and can be easily customized to suit different datasets and requirements.
