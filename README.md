## Covid Analyzer

![Coronavirus-COVID-19-AP_GB-1-1](Images/Coronavirus-COVID-19-AP_GB-1-1.jpg)

## Background:
The pupose of this study is to see if there is correlation between the number of infected people by Covid and the number of landed flights within the United States. 

## Data Sources

* COVID dataset: https://covidtracking.com/data/api
* Flight dataset: https://aviationstack.com/documentation (subscription required)

## Process Flow

1) COLLECT SOURCE DATA-Gather airport incoming flights data and COVID data 

Create one final dataframe that groups together both datasets by the date and state

2) DATA OPTIMIZATION-("Project1.ipynb",states_abbrev.csv,config.py)

Analysed the Data

Remove unwanted data

Format the values for calculations

Add rows needed to compare Data

3) DATA VALIDATION-( FullDataSet.csv, Coronavirus-COVID-19-AP_GB-1-1.jpg)

Test data thourghougly and frequently

Adjust scripts created by teammates to further fit data needs

Create additional scripts for necessary for deeper analysis

4) VIZUALIZATION-("Final_Graph.ipynb","Flight_Correlation_Work.ipynb", ChiTest.csv, FullDataSet.csv)

Quick Description

of the final dataframe

Monthly breakdown of the Infected people and a high level correlation  

5) RUN ANALYSIS(ChiTest.csv)

Prove whether or not our hypothesis holds true. 

Test how accurate our predictive equation is




