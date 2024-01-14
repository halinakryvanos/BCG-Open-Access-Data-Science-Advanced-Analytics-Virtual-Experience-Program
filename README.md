# BCG-Open-Access-Data-Science-Advanced-Analytics-Virtual-Experience-Program  

PowerCo - a major gas and electricity utility who is concerned about losing customers. PowerCo has had declining profits due to significant customer churn. We have been engaged to drive churn reduction within their Small & Medium Enterprise (SME) customers.  

# Tasks  

## 1. Business Understanding & Problem Framing
Formulated the hypothesis as a data science problem and outlined the basic steps required to test the hypothesis. Communicated his thoughts and findings via email to his LDS, focusing on potential data that might be needed from the client and the analytical models that would be used to test such a hypothesis.

The client has sent over 3 data sets (find it in Folder Raw Data):  
1.Historical customer data: Customer data such as usage, sign up date, forecasted usage etc  
2.Historical pricing data: variable and fixed pricing data etc  
3.Churn indicator: whether each customer has churned or not  

I analyzed it the following using Python:  
- The data types of each column  
- Descriptive statistics of the dataset  
- Distributions of columns  

## 2. Exploratory Data Analysis Starter  
EDA Summary  
### Findings:
- Approximately 10% of customers have churned  
- Consumption data is highly skewed and must be treated before modelling  
- There are outliers present in the data and these must be treated before modelling  
- Price sensitivity has a low correlation with churn  
- Feature engineering will be vital, especially if we are to increase the predictive power of price sensitivity  

### Suggestions:  
- Competitor price data - perhaps a client is more likely to churn if a competitor has a good offer available?  
- Average Utilities prices across the country - if PowerCo’s prices are way above or below the country average, will a client be likely to churn?  
- Client feedback - a track record of any complaints, calls or feedback provided by the client to PowerCo might reveal if a client is likely to churn 


## 3. Feature Engineering
Feature engineering is one of the keys to obtaining predictive information through mathematical modeling. Based on the available and cleaned data, it was determined what could cause customer churn and the creation of these functions for subsequent use in the model.

## 4. Prediction Model Random Forest Classifier.  
Built a churn model to try to predict the likelihood of any customer churn, taking into account all the explanatory variables that were created during the feature development process. Model evaluation.

## 5. Executive Summary 
Insights & Recommendations: how we can communicate the value of these predictions by explaining them in a way that matters to the business.
