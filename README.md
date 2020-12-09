# Machine-Learning

![](https://bfaglobal.com/wp-content/uploads/2020/01/machinelearning.jpg)

## **Machine Learning**
This assignment is about evaluating several machine-learning models to predict credit risk using free data from LendingClub. Credit risk is an inherently imbalanced classification problem, so I used different techniques for training and evaluating models with imbalanced classes. 
I used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

### **Resampling**
Imbalanced learn library for resampling the LendingClub data and building and evaluating logistic regression classifiers using the resampled data.

**Findings**

Which model had the best balanced accuracy score? 
- Naive Random Oversampling 

Which model had the best recall score? 
- Cluster Centroids 

Which model had the best geometric mean score? 
- SMOTE

### **Ensemble Learning**
Used two different ensemble classifiers to evaluate each model and predict loan risk and . As well as the Balanced Random Forest Classifier and the Easy Ensemble Classifier.

**Findings**

Which model had the best balanced accuracy score?
- Easy Ensemble Classifier

Which model had the best recall score?
- Easy Ensemble Classifier

Which model had the best geometric mean score?
 - Easy Ensemble Classifier
 
 What are the top three features? 
 - (0.09175752102205247, 'total_rec_prncp') 
 - (0.06410003199501778, 'total_pymnt_inv')
 - (0.05764917485461809, 'total_pymnt')