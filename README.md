# Lending Club 
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.To Understand the driving factors  behind loan default, i.e. the variables which are strong indicators of default.


## Table of Contents
* [General Info](#general-information)
  - [Business Understanding](#business-understanding)
  - [Business Objective](#business-objective)
  - [Data Understanding](#data-understanding)
* [Technologies](#technologies)
* [Process](#process)
* [Recommendations](#recommendations)


## General Information

In this case study we will try and develop a basic understanding of risk analytics in banking and financial services.and understand how we can minimise the risk of losing money while lending to customers.

### Business Understanding

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

### Business Objective

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

### Dataset Understanding

The data given ("loan.csv") contains information about past loan applicants and whether they ‘defaulted’ or not. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

You can access the data dictionary which describes the meaning of the variables in data set from the file name "Data Dictionary"


## Technologies 
- Python Version 3.0
- Numpy
- Pandas
- Matplotlib
- Seaborn


## Process
This is how the process carried on.
- Data Cleaning
- Univariate Analysis
- Bivariate Analysis
- Recommendations

## Recommendations 

These are recommendations we can make from the Analysis of the above loans data:
1. Verify the loans if the loan amount is less (Verification Status and Funded Amount by Investors)
2. Give loans to the right purpose. The loans for the debt consolidation, small business, and credit card types are riskier. (Purpose).
3. Make changes to the duration of a loan term. (Term)
4. Mortgage Loans bring you loss. So avoid them. (Home Ownership)


## Contact
Created by [sunkannah346@gmail.com] - feel free to contact me!

