<p align='center'> I have developed a Health Insurance Cross Sell Prediction Model</p>
<h1><p align='center'> HEALTH-INSURANCE-CROSS-SELL-PREDICTION Model Development.</p></h1>
<p align="center"><img src="https://github.com/sky309/HEALTH-INSURANCE-CROSS-SELL-PREDICTION/blob/main/INS-1-780x405.jpg"></p>

<b>Problem Statement: </b>
Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

<p> This file includes a csv file which has data of all the previously insured customer. Some customer has purchased vehicle insurance also form the company.<p>
  <b><p> Features are as below:</p></b>  
<ol>
    <li>Gender                381109 non-null  object</li> 
    <li>Age                   381109 non-null  int64 </li> 
    <li>Driving_License       381109 non-null  int64  </li>
    <li>Region_Code           381109 non-null  float64</li>
    <li>Previously_Insured    381109 non-null  int64 </li> 
    <li> Vehicle_Age           381109 non-null  object </li>
    <li>Vehicle_Damage        381109 non-null  object</li> 
    <li>Annual_Premium        381109 non-null  float64</li>
    <li>Policy_Sales_Channel  381109 non-null  float64,/li>
    <li>Vintage               381109 non-null  int64  </li>
    <li> Response</li>   </ol>
  
# This Notebook will cover :
Exploratory Data Analysis
Data Modelling and Evaluation
# Steps:
Installing and Importing Libraries
Import Dataset and Initial Data Checks
Data Preparation and Cleaning
Exploratory Data Analysis
Data Preprocessing and Feature Engineering
Cleaned Data Exporting
Hyperparameter Tuning
Building Prediction Systems using ML Models
Classifier Performance Analytics


# Inferences and Conclusions:
We've drawn many interesting inferences from the health_insurance-cross-sell-prediction data , here's a summary of the few of them:
this is confirmed with both the bivariate analysis of each feature ,as well as the Feature Importanaces returned by the notebook.
# Conclusions:
Customers of age between 30 to 60 are more likely to buy insurance.
Customers with Driving License have higher chance of buying Insurance.
Customers with Vehicle_Damage are likely to buy insurance.
The variables : Age, Previously_insured,Annual_premium are more afecting the target variable.
comparing ROC curve we can see that Random Forest model preform better. Because curves closer to the top-left corner, it indicate a better performance.


![-----------------------------------------------------](https://github.com/sky309/HEALTH-INSURANCE-CROSS-SELL-PREDICTION/blob/main/images.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Sarvesh > | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>
