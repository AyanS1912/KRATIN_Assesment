# KRATIN_Assesment

# Dementia Prediction in Elderly people.

## Introduction
This project focuses on predicting the severity of dementia, with potential outcomes being "non-demented," "demented," and "converted." The aim is to provide insights into the state of dementia for individuals, helping them and their caregivers make informed decisions.

## Dataset
The dataset used in this project contains the following features:

Subject ID: Identifier for each subject

MRI ID: Identifier for each MRI scan

Group: Dementia severity group ("non-demented," "demented," "converted")

Visit: Number of visits for each subject

MR Delay: Delay in performing MRI after the first visit

M/F: Gender of the subject

Hand: Handedness of the subject

Age: Age of the subject

EDUC: Years of education

SES: Socioeconomic status

MMSE: Mini-Mental State Examination score

CDR: Clinical Dementia Rating

eTIV: Estimated Total Intracranial Volume

nWBV: Normalize Whole Brain Volume

ASF: Atlas Scaling Factor


## Dementia Severity Groups
Non-Demented: Individuals without signs of dementia.

Demented: Individuals diagnosed with dementia.

Converted: Individuals whose dementia status changed during follow-up visits.

## Machine Learning Workflow
1) Data Collection
     
2) Data Preprocessing:
  Handling missing values.
  Normalizing numerical features.
  Encoding categorical features.

3) Training the Model:
  Splitting the dataset into training and testing sets.

4) Model Selection:
   Using a Voting Classifier with Support Vector Machine (SVM), Random Forest, and AdaBoost algorithms.
   Training the model on the training set.

5) Model Evaluation:
  Predicting dementia severity on the test set.
  Evaluating the model using the F1 score, considering the macro-average.

## How it can be helpful?
This project aims to contribute to a healthier and better life for individuals like Sunita Sharma (65+ years old) by providing early insights into the severity of dementia. The predictions can assist caregivers and healthcare professionals in making proactive decisions, potentially improving the quality of life for those at risk.

Project like such can help us in future by prevention of such disease and make elderly people have better healthier life.
