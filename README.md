# Zodiac_MBTI
Brain Storming: 
    We wanted this to be a fun and low stakes topic, exploring how Astrology Signs and Myer Briggs Types could connect.  
    
Purpose:
   The purpose of this project was to use Machine Learning as well as previous technologies we learned in the Boot Camp to solve, analyze, and visualize a          problem.

Data Gathering:
    Via Kaggle (https://www.kaggle.com/datasets/dakotagravitt/mbti-and-birthdays)
    Googled: Astrology sign personality traits, which in turn took us all to magazine sites.

We downloaded the CSV and used Python to clean the data and prepare it for creating machine learning models. This included dropping columns, adding columns, using for-loops, creating dictionaries, and other methods to preprocess the data.

For our first attempt at creating a machine learning model we tried to use sun sign personality traits to predict sun signs. However, because personality traits were not in the original dataset, we at first tried to add personality traits to each person based on the sun sign. This resulted in a 100% prediction rate, as the sun signs all had identical personality traits. We didn't consider how adding identical sets of traits for each sign would mean that the model would not work as we'd hoped. 

Process:
  - Added the same traits for each zodiac sign, created new columns for each trait
  - Created new dictionary of MBTI traits for each type of the 16 types, using the 8 letters in combinations of 4 (E,I,N,S,T,F,J,P)
  - Sun sign and traits
  - Used for-loop to give 0,1
  - Logistic Regression for predictions

Attempted Iterations:
    - Sun sign personality traits as dimensions, sun sign as target
    - Expanded MBTI personality traits as dimensions, sun sign as target
    - MBTI types as dimensions, sun sign as target 
    - Expanded MBTI personality traits as dimensions, birth month as target
    - Birth month as dimension, introversion as target
    - Sun sign as dimension, extroversion as target
    - 4 elements (earth, air, fire, water) as dimensions,  MBTI type as target (.2% accuracy) 
    - Reddit timestamp of quiz taken as dimension,  MBTI type as target  

Created a Tableau workbook to visualize the distribution of Sun Signs and MBTI Types within the dataset.
 
<<<<<<< HEAD
Overall findings: After several attempted iterations, we found the data was not big enough to give a definitive result.

<<<<<<< HEAD
Summary: Tableau map, slides(beginning numbers)  
=======
Summary: Tableau map, slides(beginning numbers)

>>>>>>> 763012b14ebba29a29410ce5542b9b9451fe287f

This project is ran in Jupyter notebook having imported the csv file.

We created the notebook with the use of Machine Learning, comparing Myers Briggs traits to Astrology signs.

=======
Overall findings: 
    After several attempted iterations we were unable to create a model with an accuracy rate above 75%. Our data set was quite small and also self-reported --      these factors could have contributed to the failure of our model.
  
>>>>>>> b500c7b27f0fd33b28f24f402fd886b9bbc3b07f
Created by:
    Kendal Bergman
    Lewis Johnson
    Jo Ann Millegan
    Seth Carlyon

<<<<<<< HEAD
    
            
=======
     
>>>>>>> 763012b14ebba29a29410ce5542b9b9451fe287f
