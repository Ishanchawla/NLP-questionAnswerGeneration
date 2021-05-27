# NLP-Classification

# Question Answer Generation

We will try to create Question and Answers from a given text. Below are the Steps involved.

1. Data Loading
2. Exploratory Data Analysis and Transformation
3. Feature Engineering
4. Model Building
5. Summary and Model Deployment

## Data Loading

We have taken data from below link for our project-

https://www.kaggle.com/stanfordu/stanford-question-answering-dataset

## EDA

a. Removal of in significant columns
b. Exploring and understanding data

## Feature Engineering

After exploring the data we did Named Entity Recognition from our text to extract entities which will act as or answers. Further details of the words from our text were extracted like Part of Speech(POS), Stop Words etc to generate features to be used in our Model Preparation.

## Model Building

Algorithms tested:

1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Random Forest
5. Ada Boost
6. Bagging Classifier

## Summary

On analysing above models we concluded with Naive Bayes as the highest performing model which predicting the answers.

## Model Deployment

1. Final Naive Bayes model was used to generate answers from the text.
2. Using Flask UI was created to input text as below and generate question and answers from it.
i. Direct Text
ii. From Text File
iii. From URL
