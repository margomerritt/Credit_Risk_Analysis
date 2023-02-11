# Credit Risk Analysis

## Overview

### Purpose

This project utilizes Python to build and evaluate several machine learning models to predict credit risk.  Being able to predict credit risk with machine learning algorithms can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud. Machine learning techniques are used in this project to help FinTech firms continuously analyze large amounts of data and predict trends to optimize lending. 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Project employs different techniques to train and evaluate models with unbalanced classes. The libraries imbalanced-learn and scikit-learn are used to build and evaluate models using resampling. The data source for this project is a credit card dataset from LendingClub, a peer-to-peer lending sevices company. The data is oversampled using the RandomOverSampler and SMOTE algorithms. Data is undersampled using the ClusterCentroids algorithm. The SMOTEENN algorithm is used to give a combinatorial approach of over- and unersampling. Two new machine learning models that reduce bias are compared to predict credit risk. 



### Software
* Data Source: LoanStats_2019Q1.csv
* Software: Python, Jupyter Notebook, Pandas, numPy

## Results

* Naive Random Oversampling

Balanced Accuracy Score:

![Screen Shot 2023-02-11 at 2 23 34 PM](https://user-images.githubusercontent.com/111299372/218277274-e35a5d9f-0fcf-40d9-92a3-07acc89d7491.png)


Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 23 42 PM](https://user-images.githubusercontent.com/111299372/218277285-48f0bc37-c6aa-47bf-89a6-adfad3cfe54e.png)



* SMOTE Oversampling

Balanced Accuracy Score:

![Screen Shot 2023-02-11 at 2 25 38 PM](https://user-images.githubusercontent.com/111299372/218277361-93aac58e-9bef-4888-847b-b3b978f284fc.png)

Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 25 43 PM](https://user-images.githubusercontent.com/111299372/218277379-3543464e-7bc7-49fe-a1b8-b427f3d4100d.png)



* Undersampling

Balanced Accuracy Score:

![Screen Shot 2023-02-11 at 2 26 49 PM](https://user-images.githubusercontent.com/111299372/218277446-c1e2c083-7212-4f33-87ee-d4403c109c92.png)

Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 27 57 PM](https://user-images.githubusercontent.com/111299372/218277458-62d3b0c3-a325-4417-9b16-f5760a9a181d.png)


* Combination Over and Under Sampling
* Balanced Random Forest Classifier
* Easy Ensemble AdaBoost Classifier

## Summary
