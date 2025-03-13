# Soccer-Success-Simulator---Sports-Analytics-Final-Project
## Executive Summary:
Using R programming language, I collaborated with three other students in order to merge multiple European soccer league data sets together in order to use Ordinal Logistic Regression to predict where teams would finish in the standings in their respective leagues based on several factors.
1. How much money is spent by the teams.
2. Number of goals conceded and scored.
3. Average age and possession rate.
4. Placed all factors in a ordinal logistic regression model to create predictions.

## Business Problem:
We wanted to create a way to simulate where a team would be predicted to finish in their respective leagues based on several factors such as number of goals conceded and scored, how money is spent by the team on transfers, squads age, possession rate, and where they play. In essence we wanted to create a soccer simulator which could be used as a tool by different soccer teams to see where they could improve in order to increase their chances of finishing higher up in their respective leagues standings. 

## Methodology:
1. Cleaned and transformed the data which included merging all the data sets together.
2. Using R, conducted some Exploratory Data Analysis to figure out further insights and what factors to add to our model.
3. Used Ordinal Logistic Regression to create our model to create our predictions.
4. Created Visualizations showcasing the simulation of where a team may end up in their respective league.

## Skills:
R: Tidyverse, ggplot2, plotly, dplyr, MASS library for ordinal logistic regression  
Data Cleaning   
Exploratory Data Analysis   
Modeling    

## Results 
We created two different models using Ordinal Logistic Regression where the first model incorporated data such as Wins, Losses, Possession, Annual wages, Expected goals against, Expected goal difference, and Goals for. The second model incorporated Goals for, Goals against, Possession, Age, and Annual Wages. What we found when running our models and testing the assumptions for Ordinal Logistic Regression, is that the first model had a higher value for the higher variance inflation factor while the second model had a lower value for the higher variance inflation factor. When deciding on which model to use to make predictions, we decided on using the second model because of the lower value of the higher variance inflation factor as well as because it was a simpler model.

![Alt Text](https://github.com/Anand1490/Soccer-Success-Simulator---Sports-Analytics-Final-Project/blob/main/Models.PNG)    

## Next Steps:  
1. The data set we used had data from multiple years and to have a more comprehensive model should look for data with even more years.
2. Further fine tune the model to create a balance of adding more variables along with a lower value for the higher variance inflation factor. 

