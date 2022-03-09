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
- Total ~5000 loans those are charge off.
- Total >30000 loans those are fully paid.
- Maximum number of loans are charged off for the those who are living on rent.
- Maximum number of loans are charged off for the loan taken for debt_consolidation.
- Maximum number of loans are charged off for the loans applied for 36 months of Loan Term.
- Maximum number of loans are charged off for the loans belong to Grade B and C.
- The intrest rate has an negative correlation with the Annual Income.
- The Loan Amount and Funded amount shares an positive correlation.
- The Gade A and Grade B people are much safe as compare to the Grade F and G.

## Technologies Used
- NUMPY: 1.20.3
- PANDAS: 1.3.4

## Contact
Created by:
- Abhishekh Pareshkumar Shah [[https://github.com/abhi-alone]]
- Rishabh Anand [https://github.com/Rishabhanand1994]