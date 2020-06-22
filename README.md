# Myprojects
Here will be the list of all the projects I have done and the updates on them :

1) IBM Watson Personality Insights



**IBM Watson Personality Insights:**

**Scope Of The Project:**
To use an api connection to IBM watson personality insight to get Big5 scores for both fictional characters and real people.

**Description Of The Project:**
This was my first individual data science project, I took script from HARRY POTTER movies from kaggle and then
connected to api of IBM WATSON PERSONALITY INSIGHTS. Then assigned individual confidence intervals of Big5 scores for each houses.

Based on these scores I then took datasets of the celebrities with their Big5 scores (based on their tweets) and tried to sort them into HOGWARTS houses.

**Language Used:** Python

**Tools Used:** 
1.Jupyter Notebook 
2.Tableau

**Skills Used:**
1. Data Cleaning 
2. API connection
3. Data retrieval
4. Data Analysis

**Steps Followed:**
1. Download the harry potter movie script having characters and their dialogues dataset from Kaggle
2. Import the file in the notebook and do the data cleaning
3. Connect to the ibm api and process the dataset to get a new dataset containing Big5 score for each character
4. Clean the retrieved dataset from ibm api
5. Analyse to find the Big5 scores and set confidence intervals for each house
6. Check the rankings of houses wrt to Big5 scores and fan ratings and see whether the hypothesis is correct or not
7. Import a new dataset with celebrities and their Big5 scores based on their tweets
8. Analyse to check their mean scores and see if they fall into the confidence intervals created earlier.

**Goal of the project:** To sort the celebrities into  HOGWARTS houses based on their average Big5 scores
