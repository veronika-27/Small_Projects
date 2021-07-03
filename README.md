# Small_Projects
Small projects and exercises from the course  
1. House sales prices - predicting housing prices using linear regression model 
2. Analyzing US Economic Data and Building a Dashboard - basics of pandas and python 
3. Visualization (2 visualization exercises mostly applying matplotlib)

House sales prices:
I had to analyze and predict the housing prices (based on some data for the period May 2014 – May 2015) in King County, USA using features such as square footage, number of bedrooms, number of floors and so on. The basic libraries I have used were:  sklearn, pandas, numpy, seaborn and matplotlib, etc. I have imported the data, have obtained some basic statistical summary. After that the data wrangling has been applied (renaming some columns, finding and handling some NaN data properly – using the mean of the variable). The next step was the exploratory data analysis – when finding some correlations between different features in order to figure out the best ones for the model. On the stage: Model development the linear regression has been used in order to predict the future house prices based on list of features. The final stage was Model evaluation, where I have split the data into test and train sets. I have used the ridge regression to evaluate the model performance (calculating the R2) and I have performed another evaluation performing second order polynomial transformation on both (test and train) sets and using again ridge regression to calculate the R2 and evaluate the model. 

Analyzing US Economic Data and Building a Dashboard:
In this small project I had to extract the essential data from a dataset about US GDP and Unemployment rate and display it. I have used some basic pandas functions and have crated some dashboards. 

In ex.visualization and  ex.visualization1 notebooks I have used some basic visualization functions (mostly of matplotlib). 

