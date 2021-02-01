# predict_heart_disease_machine_learning_project

**Overview**

This project uses the Cleveland Heart Disease UCI dataset located on [Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci).  

The project notebook includes code, visualizations, and interesting facts about heart disease and its contributing factors.

The goals of the project are to:

    1. Perform exploratory data analysis
    2. Apply a predictive machine learning algorithm 

**About the dataset**

The UCI repository contains three datasets on heart disease. 

Each dataset contains information about several patients suspected of having heart disease such as whether or not the patient is a smoker, the patient's resting heart rate, age, gender, etc. The patients were all tested for heart disease and the results of that tests are given as numbers ranging from 0 (no heart disease) to 4 (severe heart disease). 

This project uses the Cleveland Heart Disease dataset and the 14 features contained within it.

#Project Notebooks

**heart_disease_uci.ipynb**
    
    Presents the project questions and each feature in the dataset.
    
    For each variable, the following steps are taken:
    1. list relevant interesting facts, often with a link to more information
    2. list the range of values using the .unique() method
    3. plot the distribution of values with a Seaborn histogram
    4. if needed, sort the values to identify the high/low values using the .sort_values() method
    5. if needed, assign the values to a meaningful category (ex: healthy vs. high blood pressure) using the binning method
    6. if needed, calculate the percentage of values in each category and plot the percents using a Matplot Lib pie chart
    
**Feature Analysis.ipynb**

   This notebook displays plots of each feature, in order to drive decision-making about Machine Learning problem approach.
   
**Machine Learning Prediction.ipynb**
   work in progress
