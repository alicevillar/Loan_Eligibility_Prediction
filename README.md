 
# Loan Prediction using Decision Tree and Support Vector Machine
 
The repository contains a loan eligibility prediction based on a [Kaggle dataset](https://www.kaggle.com/ninzaami/loan-predication)

## Dependencies:
 
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [SciKit-Learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
 
## Approach 

This project is organized in three parts:

#### PART 1: Data Handling

* Importing Data with Pandas
* Cleaning Data
* Data description  

#### PART 2: Data Analysis

* Supervised Machine learning Techniques: + Decision Tree Model + Support Vector Machine (SVM)  

#### PART 3: Valuation of the Analysis

* K-folds cross validation to evaluate results locally 

## Summary

In Part 2, the accuracy score I found for the Decision Tree and SVM was: 

* Decision Tree  => Accuracy score = 0.7916666666666666
* Suport Vector Machine => Accuracy score = 0.7708333333333334

In Part 3 I used kfold (model validation technique) to both algorithms: 

* Applying Kfold to the Decision Tree result => 0.8
* Applying Kfold to the Support Vector Machine result  => 0.7854166666666667
 
Applying Kfold, it has been demonstrated that the Decision Tree and Support Vector Machine models are not overfitting and therefore valid.
