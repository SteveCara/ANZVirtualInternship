# ANZ Virtual Internship - Banking Predictive Analytics: Project Overview

Undertook exploratory data analysis obtain key insights from transaction sample data for Asutralia and New Zealand Banking Group (ANZ). Created linear regression and decision-tree models to predict salaries. The generated predictions were 50% more accurate than the decision tree used in the ANZ model solution. 

- Undertook exploratory data analysis to derive insights from sample transaction data for Australia and New Zealand Banking Group (ANZ)

- Converted the dataset into a timeseries to facilitate time series analysis with different levels of granularity

- Carried out data segmentation and visualisation to show the relationships between different features 

- Explored the correlation between different customer attributes to identify suitable metrics to be included in a predictive model

- Created linear regression and decision-tree models to predict salaries.

- Generated predictions for submission to ANZ. The model was able to generate predictions which were 50% more accurate than the decision tree used in the ANZ model solution.

## Resources

**Python Version:** 3.7

**Packages:** pandas, numpy, matplotlib, seaborn, geopandas, calendar, scipy, folium

**Project Basis:** Virtual Internship with ANZ

## Exploratory Data Analysis

 This consisted of the following stages:

- Examined transaction data looking for inconsistencies, missing data and found outliers by calculating Z-score

- Cleaned the data using ordinal mapping and filling of missing values and outliers with statistical best fit values

- Converted the dataset to a timeseries to facilitate time series analysis

- Segmented the data into monthly, daily and hourly transaction volumes to facilitate analysis with different levels of granularity

- Visualised transaction volumes to derive key insights about the data, including spatial density (using a folium heatmap)  

Some highlights are below.

![image]
![image}
![image]


## Predictive Analytics

For this stage I was tasked with creating a predictive model to estimate salary information. this consisted of the following stages:

- Undertook initial analysis to identify which features would be suitable for inclusion in a predictive model 

- Explored correlations between annual salary and various customer attributes including age, bank balance, and average non-salary payment amount. 

- Created and trained linear and decision-tree models and assessed model performance against the validation data set (decision-tree was the best performing model) using mean absolute error as the assessment criterion

- Undertook hyperparameter tuning to optimise the decision-tree model and generate predictions for salaries (MAE ~ $14k AUD)

Some highlights are below.

![image]
![image}
![image]

## Reporting

I created a presentation for the programme manager which synthesised the insights that were obtained from the analysis and predictive model. 
 




