# Capstone_Project
Capstone Project for Flatiron School DS 021720

# Home Loan Default Predictions

**The Project:**
  For my Capstone project I chose to do a data analysis over the Home Default Credit Risk competition on Kaggle.

**The Goal:**
  The focus of this project is to create a model that can predict if an individual will default on their home loan or not. Once the predictions are done we will list the features that affect the result the most and present it as a potential risk factor to the customer.

**The Problem:**
* There are many factors that affect the results
* There are many underlying circumstances that aren't apparent at first glance

**The Solution:**
* The model will be able to comb through the data and find the biggest factors that alter the result
* The suggestions could help prevent future customers that default on the loans

**The Process**

1. Explore & Clean data 
2. Model the data
3. Find the feature importances to list out to see which factors were the biggest contributors

**The Data:** 

The [data](https://www.kaggle.com/c/home-credit-default-risk/overview) was provided by the Home Default Credit Risk Competition on Kaggle

**The Metrics:** 

The main metric used was ROC_AUC scoring.

**The Models Chosen:**
* The baseline model - Random Forest
* Other models used - Gradient Boosting

# Conclusion
Conclusion for Project Presentation:

The 5 Most important features for the age range of 20-30 is as follows:

* 1. How many days before the application the person started current employment
    * Majority of the individuals were only employed for a short amount of time
* 2. The population density of the individual's home address
    * Most of the individuals lived in low density areas so outside of cities or other crowded residential areas
* 3. The amount of the loan
    * This amount flucuated a lot but it was most of the time 3 times higher than the income of the individual
* 4. If the household had a child or not
    * Most of the individuals that defaulted had 0 or only 1 child
* 5. Occupation Type
    * The data shows most individuals that defaulted were ones that were in lower paying jobs designated "laborer"
    
The 5 Least important features is:

* 1. The number of payments left on the loan
    * The rate at which the individual defaulted on the loans wasn't dependant on how much longer they had left to pay off the loan
* 2. The Size of the family
    * The number of family members living under the same household didn't affect the risk much
* 3. The region rating
    * Value set by the original dataset rating the quality of the living establishment
* 4. If an individual had multiple addresses listed under different categories
    * Many of them had different addresses listed under their work/personal/contact seperately
* 5. If an individual had a phone or not

# Future Recommendations
1. Gather more data with less null values
2. Apply feature engineering to improve model performance

# Repository Guide

**Notebooks**
* [Data Clean Up With Baseline Model](https://github.com/Tyasuoka/Capstone_Project/blob/master/Jupyter_Notebooks/Modeling.ipynb)

**CSV Files**
* [Original Data](https://github.com/Tyasuoka/Capstone_Project/blob/master/CSVs/Base_Train.csv.zip) - Only the Base Train dataset was small enough when compressed to be uploaded onto GitHub
* [Cleaned Data](https://github.com/Tyasuoka/Capstone_Project/blob/master/CSVs/Model_Ready_Data.csv.zip)

**Presentation**
[Canva Link]()

# Resources

**The Data:**

The raw datasets were too big for github so they have not been added to this Repository.

The data is based off of [this](https://www.kaggle.com/c/home-credit-default-risk/overview) Kaggle Competition.

**Models:**

Below you will find model documentation

* [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
* [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
* [Inspiration from Kaggle Competition Notes](https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction)
 
# Human Resources
* My Last Data Bender Cohort 02/17/20 classmates
* Lindsey Berlin DS 02/17/20 Instructor 
* Bryan Arnold DS 002/17/20 Instructor
