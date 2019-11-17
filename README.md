# Loan-Predictor
An intelligent system based on data mining that can predict whether it is better to give loans to a customer based on their diabetes reports.
## Table of Contents
[Introduction](#Introduction)
[Requirements](#Requirements)
[How-To-Use](#How-To-Use)
[Dataset](#Dataset)
[Technical-Details](#Technical-Details)
[Algorithm](#Algorithm)
[Lisence](#Lisence)
### Introduction
Loans are integral part of banking trnsactions.When a bank has to issue a loan there will be many parameters to be considered like customer health condition,his previous credit history ..etc.Here we are considering women of different age groups and their diabetes reports to conclude whether to give loan or not. In general the bank officials do some manual work to come to a conclusion. But this is less reliable and moreover time consuming. So the objective of this project is to design an intelligent system that can suggest to give loan to a particular woman or not.
### Requirements
Python 3.5 or above version with pandas,matplotlib,scikit-learn,seaborn and pickle packages.
Jupyter lab/Jupyter notebook
No specific hardware requirements and runs on any operating system
### How-To-Use
After downloading and extracting the repository open it in jupyter notebook.Then open the `loan_predictor.ipynb` file.In that file change the values of `diabetes_report` variable.
The order of the values are `'Pregnancies','Glucose','BloodPressure','Insulin','BMI','DiabetesPedigreeFunction','Age'` and then run all the cells.The conclusion whether to give the loan or not will be displayed as output of the last cell.

### Dataset
The dataset used in this project is diabetes.csv dataset from kaggle datasets.
The dataset can be downloaded from <https://www.kaggle.com/saurabh00007/diabetescsv>
### Technical-Details
##### Dataset Details
The dataset contains 9 attributes and 298 instances.
The column details are
Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Outcome
##### Files Organization
The project is implemented in python in Jupyter Notebook environment.It mainly contains two parts.The `loan_trainer.ipynb` is for training the data and the `loan_predictor.ipynb` is to load the trained data and to predict results.The `laon_model.sav` is the model that is saved.The `diabetes.csv` is the file that contains the dataset in comma seperated values format.
### Algorithm
The Loan Prediction is a type of classification problem.As here there are only two types of target values this comes under `binomial classification`.
The algorithm used in this is `Decision Tree`.More details about this algorithm can be found at <https://en.wikipedia.org/wiki/Decision_tree>
### Lisence
This is a public repository and you can be used in research,commercial and non-commercial applications without any restrictions.

