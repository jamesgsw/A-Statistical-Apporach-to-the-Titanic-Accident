# A Statistical Approach to the Titanic Accident

## Table of Contents
* [1. About the  Project](#point_1)
* [2. Personal Motivation for this project](#point_2)
* [3. Findings](#point_3)
    * [3.1 Exploratory Analysis](#point_3_1)
    * [3.2 Correlation Matrix](#point_3_2)
    * [3.3 Regression and Machine Learning Models](#point_3_3)
* [4. Usage](#point_4)
* [5. Datasets](#point_5)


<a id= "point_1"></a>
##  1. About the  Project
The goal of this project is to utilised the dataset provided from Kaggle website to analyse the possible factors that affecting survivability and creating a prediction model for survivability of passengers using variables from the dataset for the Kaggle Titanic Competition


<a id= "point_2"></a>
## 2. Personal Motivation for this project
In addition, my personal goal for this project is to use this project as an application for my university module on Statistics, to make use of the statistical tools to create inference, analysis through hypothesis testing and finally creating regression models. The Statistical methods I applied are: ANOVA, Chi-Squared Test, Bonferroni Method, Regression Modelling(Logistics & Linear Regression), Ordinal & Nominal Encoding, and Correlation Coefficient.


<a id= "point_3"></a>  
## 3. Findings

<a id= "point_3_1"> <b> 3.1 Exploratory Analysis </b> </a>  
For the analysis component of the project: Through the statistical test conducted, I've found that the factors that had the biggest impact on the survivability of passengers are the Fare, Sex, Ticket Class, Port of Embarkation and Size of family. While the age, Social Status and Ticket Number had little statistical significance with the survivability of passengers.  
<img width="394" alt="Exploratory Analysis" src="https://user-images.githubusercontent.com/36501392/82296296-9387d500-99e3-11ea-828d-20a2f982b466.png">

<a id= "point_3_2"> <b> 3.2 Correlation Matrix </b> </a>  
The correlation matrix gives an overview the coefficient of determination for the different factors, which will be subsequently used in point 3.3 Regression and Machine Learning Models.  
<img width="977" alt="Correlation Matrix" src="https://user-images.githubusercontent.com/36501392/82296324-9b477980-99e3-11ea-980f-c1ffcea7fbca.png">


<a id= "point_3_3"> <b> 3.3 Regression and Machine Learning Models </b>  </a>  
For the forecasting component of the project: We tested various regression and machine learning algorithms, and evaluated their performance based off the mathematical score and validation algorithm. Through this evaluation, I determined that the Logistics Algorithm delivered the a high score within a reasonable computation time and would be my preferred algorithm to predict the survivability of passengers.


<a id= "point_4"></a>  
## 4. Usage
The jupyter notebook is available online at [this link](https://nbviewer.jupyter.org/github/jamesgsw/A-Statistical-Approach-to-the-Titanic-Accident/blob/master/Analysis%20%26%20Prediction%20for%20the%20Titanic%20accident.ipynb) if there's issues accessing through Github.


<a id= "point_5"></a>  
## 5. Files in this Repository
There are 4 files in this repo.
<br>"Analysis & Prediction for Titanic-Statistical View.ipynb" is the heart of this project with the analysis and codes inside a Jupiter Notebook file.
<br> "train.csv" is the dataset that I utilised for my analysis. "test.csv" contains the data for the test done for the Kaggle competition.
<br> The last file is this 'README.md' file given the overview of this project in plain text.
