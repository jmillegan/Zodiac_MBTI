# Zodiac_MBTI
Brain Storming: 
    We wanted this to be a fun and low stake topic, coming up with how astrology signs and Myer Briggs Types would connect.  
Purpose:
    The purpose of this project was to utilize Machine Learning as well as previous technologies we learned in Boot Camp to solve, analyze, or visualize a problem.

Data Gathering:
    Via Kaggle (website) found the dataset used (https://www.kaggle.com/datasets/dakotagravitt/mbti-and-birthdays)
    Googled: Astrology sign personality traits, which in turn took us all to magazine sights.

Download the CSV from our website.  We modified it, cleaning the birthdates to allow creation of astrology columns.
     as well as using a VLOOKUP within the CSV to identify astrology signs to MBTI.

First attempt for the model we used Sun Sign personality traits, however this resulted at 100% prediction, this was because all the data was the same.

Attempted Iterations:
    Added the same traits for each zodiac sign, created new columns for each trait.
    Created new dictionary of MBTI traits for each type of the 16 types, using the 8 letters in combinations of4          E,I,N,S,T,F,J,P
    Tested several variations of Machine Learning
            - Sun sign personality traits were perfect at 100% since data was all the same.
            - Sun sign and traits
            - Used for loop to give 0,1
            - Sun sign was target and MB was the feature (16 type using 0 1)
            - Sun sign was target using 8 traits 
            - Predict birth month by the standard MBTI traits
            - Birth month and Introversion/Extraversion highest 50%
            - Extraversion based on Sun sign 
            - Logistic Regression for predictions
            - Zodiac 4 Elements vs MB (earth air fire water) 2%
            - Using Reddit timestamp vs MB 

Creating Tableau to illustrate any trends just looking at the date in a visual way and the distribution of Sun Signs and MBTI
 
Overall findings: After several attempted iterations, we found the data was not big enough to give a definitive result.

Summary: Tableau map, slides(beginning numbers)


This project is ran in Jupyter notebook having imported the csv file.

We created the notebook with the use of Machine Learning, comparing Myers Briggs traits to Astrology signs.

Created by:
    Kendal Bergman
    Lewis Johnson
    Jo Ann Millegan
    Seth Carlyon

     
