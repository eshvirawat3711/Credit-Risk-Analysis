# Credit-Risk-Analysis

## Goal: Predict if a Loan Credit will be a risk for bank or not

In simple terms, if the loan amount is given to the applicant, will they pay back or become a defaulter?

Since there are many applications which needs to be processed everyday, it will be helpful if there was a predictive model in place which can assist the executives to do their job by giving them a heads up about approval or rejection of a new loan application.

The flow of the case study is as below:

* Reading the data in python
* Defining the problem statement
* Identifying the Target variable
* Looking at the distribution of Target variable
* Basic Data exploration
* Rejecting useless columns
* Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
* Feature Selection based on data distribution
* Outlier treatment
* Missing Values treatment
* Visual correlation analysis
* Statistical correlation analysis (Feature Selection)
* Converting data to numeric for ML
* Sampling and K-fold cross validation
* Trying multiple Classification algorithms
* Selecting the best Model
* Deploying the best model in production

# Data Description

The business meaning of each column in the data is as below

* *GoodCredit:* Whether the issued loan was a good decision or bad
* *checkingstatus:* Status of existing checking account.
duration: Duration of loan in months
history: Credit history of the applicant
purpose: Purpose for the loan
amount: Credit amount
savings: Savings account/bonds
employ: Present employment since
installment: Installment rate in percentage of disposable income
status: Personal status and sex
others: Other debtors / guarantors for the applicant
residence: Present residence since
property: Property type of applicant
age: Age in years
otherplans: Other installment plans
housing: Housing
cards: Number of existing credits at this bank
job: Job
liable: Number of people being liable to provide maintenance for
tele: Is the Telephone registered or not
foreign: Is the applicant a foreign worker
The file used for this case study is "CreditRiskData.csv". This file contains the historical data of the good and bad loans issued.

The goal is to learn from this data and predict if a given loan application should be approved or rejected!
