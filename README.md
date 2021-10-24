# Credit Risk Analysis. Project 17 of the UofT.
## `-Contents-`	
	
- [Overview of the Credit Risk Analysis](#Overview-of-the-Credit-Risk-Analysis)	
- [Resources](#resources)	
- [The Credit Risk Analysis Result](#The-Credit-Risk-Analysis-Result)
  - [Resampling Models to Predict Credit Risk ](#--Resampling-Models-to-Predict-Credit-Risk )
  - [The SMOTEENN algorithm to Predict Credit Risk](#--The-SMOTEENN-algorithm-to-Predict-Credit-Risk)
  - [Ensemble Classifiers to Predict Credit Risk](#--Ensemble-Classifiers-to-Predict-Credit-Risk)
- [The Credit Risk Analysis Summary](#The-Credit-Risk-Analysis-Summary)
## `Overview of the Credit Risk Analysis`	
	
The purpose for the project is to employ different techniques to train and evaluate models with unbalanced classes. Also, to evaluate the performance of the models and make a written recommendation on whether they should be used to predict credit risk.

The analysis consists of three technical analysis deliverables and a written report as the following: 

- Predict Credit Risk using:
  - Resampling Models;
  - The SMOTEENN Algorithm;
  - Ensemble Classifiers;
- Submit a Written Report on the Analysis.

## `Resources`	
The analysis is created using next software: Jupyter-notebook 6.3.0, Python 3.8.8, Pandas 1.2.4, machine learning libraries for Python: imbalanced-learn 0.8.1, scikit-learn 0.24.1, Visual Studio Code 1.58.0.

## `The Credit Risk Analysis Result`
### `- Resampling Models to Predict Credit Risk`	

The result of Resampling Models can be found in the [Credit_Risk_Resampling](./credit_risk_resampling.ipynb) file.

According the results of three machine learning models as Random Oversampling, SMOTE Oversampling, Undersampling it may be determined as the ______________________ltk ______________________is better to predic credit risk

Firstly, the oversampling RandomOverSampler and SMOTE algorithms were used
 
And then the undersampling ClusterCentroids algorithm. 
 
Using these algorithms, the dataset were resampled, the count of the target classes were viewed, a logistic regression classifier were trained, the balanced accuracy score, generate a confusion matrix, and generate a classification report were calculated.

balanced accuracy scores  
Naive Random Oversampling![image](https://user-images.githubusercontent.com/68247343/138608058-322834bc-7ae6-4bfb-b294-1f1bbb30c5e4.png)

SMOTE Oversampling![image](https://user-images.githubusercontent.com/68247343/138608064-d0385999-7100-45c9-aa5d-70000a6a17c9.png)

Undersampling![image](https://user-images.githubusercontent.com/68247343/138608071-0c21cf8a-af1a-4d6b-99bf-bcb03466dd61.png)

the precision and recall scores of all six machine learning models
Naive Random Oversampling![image](https://user-images.githubusercontent.com/68247343/138608120-0d88e5b2-bd31-48d7-8f72-1a6c7962bdba.png)

SMOTE Oversampling![image](https://user-images.githubusercontent.com/68247343/138608125-fd484dc8-cb9c-4425-812e-59e9724dde7c.png)

Undersampling![image](https://user-images.githubusercontent.com/68247343/138608128-5a2f0204-52df-49b6-9089-b8922a8b6efb.png)


### `- The SMOTEENN algorithm to Predict Credit Risk`
The result of the SMOTEENN algorithm can be found in the [Credit_Risk_Resampling_Models](./credit_risk_resampling.ipynb) file.

Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

balanced accuracy scores and the precision and recall scores of all six machine learning models.
Combination (Over and Under) Sampling![image](https://user-images.githubusercontent.com/68247343/138608150-766efd38-f302-4bca-bc64-0fcb6eae9173.png)

### `- Ensemble Classifiers to Predict Credit Risk`
The result of the Ensemble Classifier algorithm can be found in the [Credit_Risk_Ensemble_Classifiers](./credit_risk_ensemble.ipynb) file

Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report

balanced accuracy scores and the precision and recall scores of all six machine learning models.
Balanced Random Forest Classifier![image](https://user-images.githubusercontent.com/68247343/138608197-c506d846-22a7-4279-9a4d-24fce14b20bb.png)

Easy Ensemble AdaBoost Classifier![image](https://user-images.githubusercontent.com/68247343/138608208-7faa7a63-1733-4843-ae3b-742adfe6e41c.png)

## `The Credit Risk Analysis Summary`

According to the result of the Bias ...

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

balanced accuracy scores and the precision and recall scores of all six machine learning models.

Additionally, 
