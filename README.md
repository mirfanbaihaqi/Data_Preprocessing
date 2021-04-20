# Data Preprocessing
Data preprocessing is an important step before move to modelling using Machine Learning or Deep Learning. There are several steps in data preprocessing;
* Load Datasets
* Data Understanding
* Data Cleaning and Preprocessing inlcude Impute Missing Values and Replace Outlier
* Handle Inconsistent Data (depends on the data)
* Feature Engineering include Binning and Encoding Variables in categorical data
* Data Partition
* Synthetic Minority Over-sampling Technique (SMOTE)

## Overview
For this data preprocessing project, I took data from Telkom named telco. Data preprocessing is an important step before move to modelling using Machine Learning or Deep Learning. If the model that has been created produces less effective results, Data Scientist will return to preprocessing data. Because preprocessing data greatly affects the results of the effectiveness of the model later. Common case in data preprocessing is handling missing values, outliers and inconsistent data content.

Dividing the data into 80% training data and 20% testing data is very important. Because more and more training data is used, it will produce a good model. In addition, the model must also match or fit with the existing case.

This dataset has imbalance output. Its shown that 4136 are not churn and 1498 are churn. To handle this case, i use SMOTE so the data will turn into balance data. By using minority class to oversampling the data, i got the balance data now.

![](https://github.com/mirfanbaihaqi/Data_Preprocessing/blob/main/smote.png)
