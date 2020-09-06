# ANZVirtualInternship: Project Overview

Undertook exploratory data analysis obtain key insights from transaction sample data for Asutralia and New Zealand Banking Group (ANZ). Created linear regression and decision-tree models to predict salaries. The generated predictions were 50% more accurate than the decision tree used in the ANZ model solution. 

- Undertook exploratory data analysis to derive insights from sample transaction data for Australia and New Zealand Banking Group (ANZ)

- Completed data segmentation and visualisation to show the relationships between different features 

- Explored the correlation between different customer attributes to identify suitable metrics to be included in a predictive model

- Created linear regression and decision-tree models to predict salaries.

- Generated predictions for submission to ANZ. The model was able to generate predictions which were 50% more accurate than the decision tree used in the ANZ model solution.

## Resources

**Python Version:** 3.7

**Packages:** pandas, numpy, matplotlib, seaborn

**Project Basis:** Virtual Internship with Quantium

## Data Preparation and Customer Analytics

 This consisted of the following stages:

- Examined transaction data looking for inconsistencies, missing data and outliers

- Cleaned the data using ordinal mapping and filling of missing values and outliers with statistical best fit values

- Merged customer data with transaction data to create a unified sales dataset

- Defined performance metrics and identified total sales, drivers of sales and highest performing products

- Conducted a deep dive into customer segments to advise which segments should be targeted.  

Some highlights are below.

**Total Sales by Brand**
![image](/images/chipsales.PNG)

**Product Weights with Outliers**
![image](/images/chipweights.PNG)

**Sales Profile (All Stores) - Full Observation Period**
![image](/images/salesprofile.PNG)

This indicated that the brands with the highest sales were Doritos, Smiths and Kettle. This also revealed that sales were highest in December during the holiday season.

## Experimentation and Uplift Testing

I undertook experimentation and uplift testing to identify control stores, consisting of the following stages:

- Determined total sales revenue and total number of customers on monthly and annual bases and number of transactions per customer

- Normalised salaes values and created a metric to compare the sales performance different control stores to each of the trial stores

- Control stores were selected based on their similarity to trial stores

- The performance of trial stores was compared to the control stores to assess the impact of the new trial layout

Some highlights are below.

**Comparison of Trial and Control Store Pair**
![image](images/TrialStores.PNG)

**Trial Store Sales Perforance - Full Observation Period**
![image](images/TrialStores2.PNG)

**Trial Store vs Control Store Sales During Trial Period**
![image](images/TrialStores3.PNG)

 This revealed that the trial layout resulted in higher sales during the trial period.
 
 ## Analytics and Commercial Application
 
 In this stage, I synthesised the results from the previous stages to prepare a summary report to the client. The results informed strategy recommendations for the client. 
 
 




