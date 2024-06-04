# Life-Expectancy-Prediction

## Problem Statement 
 
"Predicting Life Expectancy using a comprehensive set of predictor variables, 
including immunization rates, mortality factors, economic indicators, social 
determinants, and various health-related factors: A multiple linear 
regression approach."

## Data Description 
 
The project relies on accuracy of data. The Global Health Observatory (GHO) 
data repository under World Health Organization (WHO) keeps track of the health 
status as well as many other related factors for all countries The data-sets are 
made available to public for the purpose of health data analysis. The data-set 
related to life expectancy, health factors for 193 countries has been collected from 
the same WHO data repository website and its corresponding economic data was 
collected from United Nation website. Among all categories of health-related 
factors only those critical factors were chosen which are more representative. In 
this project we have considered data from year 2000-2015 for 193 countries for 
further analysis. The individual data files have been merged together into a single 
data-set. On initial visual inspection of the data showed some missing values. As 
the data-sets were from WHO, we found no evident errors. Missing data was 
handled in R software by using Missmap command. The result indicated that most 
of the missing data was for population, Hepatitis B and GDP. The missing data 
were from less known countries like Vanuatu, Tonga, Togo, Cabo Verde etc. 
Finding all data for these countries was difficult and hence, it was decided that 
we exclude these countries from the final model data-set. The final merged file 
(final dataset) consists of 21 Columns and 2938 rows which meant 17 predicting 
variables. All predicting variables was then divided into several broad categories:
 Immunization related factors, Mortality factors, Economical factors and Social 
factors. 
