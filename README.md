# Project Name:Lending Club Case Study
> This project focuses on applying Exploratory Data Analysis (EDA) to a historical dataset of loan applicants from a consumer finance company. The primary goal is to analyze past loan applications to identify key factors that contribute to loan defaults. Through this analysis, the company can predict which applicants are most likely to default and take preemptive actions to minimize financial loss.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Information: The project involves the analysis of loan data from applicants over the period 2007 to 2011.
  The company is interested in understanding how various borrower and loan attributes influence the likelihood of default.
  The dataset includes information on loans that were fully paid, loans that are still current, and loans that have been charged-off (defaulted).
  The insights from this analysis will help the company make informed decisions regarding loan approvals, reduce the risk of credit loss, and improve the overall performance of the loan portfolio.

- Project Background:
The project is based on risk analytics in the context of a consumer finance company that lends personal loans, business loans, and medical financing to urban customers. When a customer applies for a loan, the company faces two key risks:
1. Loss of business if a potentially good applicant is denied a loan.
2. Financial loss if a risky applicant is approved and later defaults on the loan.

The company has observed that borrowers who default (charged-off loans) cause the largest amount of financial loss. To mitigate this, the company needs to identify high-risk loan applicants in advance using historical data, allowing them to adjust their loan approval processes and reduce credit loss.

- Business Problem:
The main problem that this project is addressing is the identification of risky loan applicants who are likely to default on their loans. If these high-risk applicants can be identified early, the company can either deny the loan, reduce the loan amount, or lend to them at higher interest rates to offset potential losses. 

The company's objective is to minimize credit loss—the money lost when a borrower defaults—by understanding the key driver variables behind loan default.

- Dataset details:
 The dataset consists of loan applications between the years 2007 to 2011.
 It includes several variables related to the borrower’s attributes (such as income, credit score, and employment status) and loan characteristics (such as loan amount, interest rate, and loan term).
 The primary target variable of interest is the loan status, with key categories being:
  Fully Paid: The borrower repaid the loan in full.
  Current: The borrower is still making payments.
  Charged-off: The borrower defaulted on the loan.

## Conclusions
- Customers with dti between 8 and 20 are more likely to default 
- Borrowers with annual income between 30k to 65k are more likely to default and higher annual income are less likely to default.
- Grade and Interest rates are correlated. Higher number of loans have been given to Grade A and Grade  B, and the percentage of defaulters increases with grade A to G. Higher grade will have higher interest rates and the percentage of defaulters increases with grade A to G. 
- customers with open accounts between 5 and 10 have more defaulters
- Loan amounts, Funded amount are highly correlated and people will less than 5k loan amount are less prone to be defaulters
- Debt consolidation seems to be the maximum purpose for taking loan and has more defaulters but if we look at proportion, Loans with purpose as ‘Small business’ are more prone to be defaulters

## Technologies Used
- NumPy package version: 1.24.3
- Pandas package version: 2.0.3
- Seaborn package version: 0.12.2
- matplotlib pacakge Version: 3.7.2
- Python version: 3.11.5

## Acknowledgements
Give credit here.
- This project was inspired by upgrad as part of EDA case study 
- References: EDA sessions from upgrad and learning content from upgrad portal

## Contact
Created by Renganayaki S, Mallibabu Balla
