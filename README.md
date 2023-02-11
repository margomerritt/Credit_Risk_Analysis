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

The calculated Balanced Accuracy Score for the Naive Random Oversampling model is 0.64.

![Screen Shot 2023-02-11 at 2 23 34 PM](https://user-images.githubusercontent.com/111299372/218277274-e35a5d9f-0fcf-40d9-92a3-07acc89d7491.png)


Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 23 42 PM](https://user-images.githubusercontent.com/111299372/218277285-48f0bc37-c6aa-47bf-89a6-adfad3cfe54e.png)

From the printed Imbalanced Classification Report we see that the average precision is 0.99 and the average recall score is 0.62.

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

Balanced Accuracy Score:

![Screen Shot 2023-02-11 at 2 28 48 PM](https://user-images.githubusercontent.com/111299372/218277501-0c2cb9df-33bd-4170-8c73-1619d81435f6.png)

Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 28 53 PM](https://user-images.githubusercontent.com/111299372/218277507-52b218fc-b41a-494b-a7c8-a2cbaf08954f.png)


* Balanced Random Forest Classifier

Balanced Accuracy Score:

![Screen Shot 2023-02-11 at 2 30 20 PM](https://user-images.githubusercontent.com/111299372/218277554-9177bcfb-32d2-4878-9dd9-0e2de287abb6.png)

Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 30 25 PM](https://user-images.githubusercontent.com/111299372/218277556-7b9c3c7c-2bd1-44b5-94f9-a3829fa80ec4.png)

* Easy Ensemble AdaBoost Classifier

Balanced Accuracy Score:

![Screen Shot 2023-02-11 at 2 31 08 PM](https://user-images.githubusercontent.com/111299372/218277582-06821010-42f3-4bd0-b5d7-62db19ce6d8a.png)

Imbalanced Classification Report:

![Screen Shot 2023-02-11 at 2 31 13 PM](https://user-images.githubusercontent.com/111299372/218277584-6dbce4b6-e2fd-4669-aa4a-429809626529.png)

## Summary
