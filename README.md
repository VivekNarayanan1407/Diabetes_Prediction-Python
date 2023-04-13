# BISI CST2101 Project - Diabetes Analysis(Vivek Anandham_041092466)
Final Project on Diabetes Analysis using Python focused mainly on Exploratory Data Analysis and Model Training as part of my Post Graduate Diploma in Business Intelligence System Infrastructure curriculum.

## Context
Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe (also known as the Pima Indians). In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima Indian heritage.

## Objective
Here, we are analyzing different aspects of Diabetes in the Pima Indian tribe by doing Exploratory Data Analysis.Then build Supervised ML Models(Logistic Regression, Random Forest) and compare the models performance using evaluation metrics.

## Data Dictionary
Below is the attribute information:
<ul>
<li> **Pregnancies:** Number of times pregnant</li>
<li> **Glucose:** Plasma glucose concentration a 2 hours in an oral glucose tolerance test</li>
<li> **Blood pressure:** Diastolic blood pressure (mm Hg)</li>
<li> **SkinThickness:** Triceps skinfold thickness (mm)</li>
<li> **Insulin:** 2-Hour serum insulin (mu U/ml) test</li>
<li> **BMI:** Body mass index (weight in kg/(height in m)^2)</li>
<li> **DiabetesPedigreeFunction:** A function that scores likelihood of diabetes based on family history</li>
<li> **Age:** Age in years<li>
<li> **Outcome:** Class variable (0: the person is not diabetic or 1: the person is diabetic)</li>
  </ul>

## Repository Contents
This repository includes a ReadMe.txt, Dataset used(diabetes.csv),
<ul>
  <li>ReadMe.txt</li>
  <li>DataSet used(diabetes.csv)</li>
  <li>Final Jupyter Notebook File(Vivek Anandham_041092466.ipynb)</li>
  <li>Final Html File(Vivek Anandham_041092466.html)</li>
  </ul>
  
## Final Inference
##### Comparing the above two models(Logistic Regression and Random Forest), we can say Random Forest perfromed better with an Accuracy on Test = 77%.
##### Also, increasing the max_depth to 5 could increase the Model Test Accuracy to 79% and False Negatives were also reduced from 14 to 11 respectively.
##### However considering its a medical domain analysis we need to improve the model accuracy by trying out other classification models too, perform feature engineering(use feature selection, handle outliers and handle features imbalance too) and employing Hyperparameter Tuning (Using GridSearchCV) to find out the best parameters for the models.
