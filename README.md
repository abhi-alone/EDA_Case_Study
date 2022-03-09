# Project Name
> Lending Club Case Study

## Table of Contents
* [Introduction](#problem-introduction)
* [Objective](#Business-Objective)
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Introduction:
This case study is to develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## Objective:
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
The main objective of this case study is to identify the risky loan applicants to reduce credit loss, using Exploratory Data Analysis (EDA). 

## General Information
When the finance company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
When a person applies for a loan, there are two types of decisions that could be taken by the company:

- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
  - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
  - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Conclusions
- The annual income graph shows the annual income of the borrower who have applied for the loan. 
 This is an important plot to understand that the people with higher income tend to be more liable to pay the loan amount. 
 Thus the bank has more trust on the people having higher income.

- This LOAN amount box plot shows the loan amount that a person goes and apply in a bank. It is observed that the higher loan amount tends to be having more Emi. Thus this plot relates with the annual income so a person with higher income may opt for a bigger loan amount.

- The Employee experience vs loan graph shows that the employee with more experience tend to fully pay the loan. 
 So an experience employee will have a high chance of being in non defaulter list.

- Correlation graph: This example shows the data plot in terms of all the relevant criteria being used. The correlation of the loan amount with the annual income suggest that annual income if being on higher side tend to help in paying the loan more easily.




## Technologies Used
# Import the libraries
from numpy import * # for scientific computing
from pandas import * # for data analysis
from matplotlib.pyplot import * # for data visualization and graphical plotting
import seaborn as sb_plt

## Acknowledgements
- References if any...
- This project was based on Exploratory Data Analysis


## Contact
Created by [https://github.com/abhi-alone] - feel free to contact me!
