# Machine Learning with Astrology & the Myers Briggs Type Indicator
## Brain Storming: 
We wanted this to be a fun and low stakes topic, exploring how Astrology Signs and Myer Briggs Types could connect.  
    
## Purpose:
The purpose of this project was to use Machine Learning as well as previous technologies we learned in the Boot Camp to solve, analyze, and visualize a problem.

## Data Gathering:
After discussing what type of project we wanted to work on, we set about finding a dataset. We were able to find a dataset in Kaggle that contained birthdate information as well as self-reported Myers Briggs Types. We hoped to find a larger dataset, but this was the only dataset we were able to find that had birthday information as well as some amount of personality trait information. 

We downloaded the CSV and used Python to clean the data in Jupyter notebook and prepare it for creating machine learning models. This included dropping columns, adding columns, using for-loops, creating dictionaries, and other methods to preprocess the data.

Via Kaggle (https://www.kaggle.com/datasets/dakotagravitt/mbti-and-birthdays).

We also Googled astrological sign personality traits, which in turn took us to many women's magazine websites.

## Process - Data Cleaning & Preprocessing:

For our first attempt at creating a machine learning model we tried to use sun sign personality traits to predict sun signs. However, because personality traits were not in the original dataset, we at first tried to add personality traits to each person based on the sun sign. This resulted in a 100% prediction rate, as the sun signs all had identical personality traits. We didn't consider how adding identical sets of traits for each sign would mean that the model would not work as we'd hoped. 

Methods:
  - Added the same traits for each zodiac sign, created new columns for each trait
  - Created a  dictionary of traits for each of the 16 MBTI types
  - Used for-loops and get dummies to transform categorical data into 0s and 1s
  - SciKit Learn's Logistic Regression models for creating a model and predictions 

Attempted Machine Learning Iterations:
    - Sun sign personality traits as dimensions, sun sign as target
    - Expanded MBTI personality traits as dimensions, sun sign as target
    - MBTI types as dimensions, sun sign as target 
    - Expanded MBTI personality traits as dimensions, birth month as target
    - Birth month as dimension, introversion as target
    - Sun sign as dimension, extroversion as target
    - 4 elements (earth, air, fire, water) as dimensions,  MBTI type as target (.2% accuracy) 
    - Reddit timestamp of quiz taken as dimension,  MBTI type as target  

We also created a Tableau workbook to visualize the distribution of Sun Signs and MBTI Types within the dataset.
 
## Summary:

This project is run in Jupyter notebook, using an imported the csv file. We created a variety of machine learning models looking at Myers Briggs types/traits and astrological signs. 

There is also a Tableau workbook and a slideshow presentation.

## Overall findings: 
After several attempted iterations we were unable to create a model with an accuracy rate above 75%. Our data set was quite small and also self-reported -- these factors could have contributed to the failure of our model.
  
Created by:
    Kendal Bergman,
    Lewis Johnson,
    Jo Ann Millegan,
    Seth Carlyon
