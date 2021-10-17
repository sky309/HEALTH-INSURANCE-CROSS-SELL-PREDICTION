<p align='center'> I have developed a Health Insurance Cross Sell Prediction Model</p>
<h1><p align='center'> HEALTH-INSURANCE-CROSS-SELL-PREDICTION Model Development.</p></h1>
<p align='center'><img src='https://www.google.com/url?sa=i&url=https%3A%2F%2Fiamcheated.indianmoney.com%2Fblogs%2Ftransfer-car-insurance-policy--things-you-need-to-know&psig=AOvVaw2305qPwH_0G_jtoLUpyaXi&ust=1634548486017000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCPDYwumN0fMCFQAAAAAdAAAAABAE'></p>
<h2>Problem Statement</h2>
Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

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
