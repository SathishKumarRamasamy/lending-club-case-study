# Lending Club Case Study
> Helping Largest Online marketplace facilitating loans to identify risky loan applicants, thereby minimizing credit loss


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
### Background
We assume we work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


The dataset considered contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

 
In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
1. **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:
    1. **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate).
    2. **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    3. **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Business Problem

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the **driving factors (or driver variables)** behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

### Analysis not considered in code for conciseness
- Univariate analysis on funded_amnt
- Univariate analysis on funded_amnt_inv
- Univariate analysis on int_rate
- Univariate analysis on installment
- Univariate analysis on Loan Grade
- Univariate analysis on Loan Sub Grade
- Univariate analysis on annual_inc
- Univariate analysis on Issue date
- Univariate analysis on State
- Univariate analysis on dti
- Univariate analysis on delinq_2yrs
- Univariate analysis on Earliest Credit Line
- Univariate analysis on Number of Inquiries in the last 6 months
- Univariate analysis on Open Credit Lines
- Univariate analysis on Public Records
- Univariate analysis on Revolving Balance
- Univariate analysis on Revolving Line Util. Rate
- Univariate analysis on Total Credit Lines
- Univariate analysis on Payment Received for total amnt
- Univariate analysis on Payment Received for total amnt by investors
- Univariate analysis on Total Received Principal
- Univariate analysis on Total Received Interest
- Univariate analysis on Total Received Late Fee
- Univariate analysis on recoveries
- Univariate analysis on Charge Off Collection Fees
- Univariate analysis on Last Payment date
- Univariate analysis on Last Total Payment
- Univariate analysis on Last Credit Pull Year
- Univariate analysis on Public Record bankruptcies
- Segmented Univariate analysis using sub_grade
- Segmented Univariate analysis using delinq_2yrs
- Segmented Univariate analysis using number of inquiries in last 6 months
- Segmented Univariate analysis using open credit lines
- Segmented Univariate analysis using Public Records
- Segmented Univariate analysis using Total Number of Credit Lines
- Segmented Univariate analysis using Total Payment
- Segmented Univariate analysis using Last Total Payment
- Segmented Univariate analysis using Number of Public Record bankruptcies
- Segmented Univariate analysis on issue_d, zip_code, addr_state, earliest_cr_line,last_pymnt_d,last_credit_pull_d
- Bivariate Analysis: Term vs Interest Rate
- Bivariate Analysis: Term vs Annual Income
- Bivariate Analysis: Term vs Revolving Credit Utilization
- Bivariate Analysis: Annual Income vs Interest Rate
- Bivariate Analysis: House Ownership vs Annual Income
- Bivariate Analysis: Term vs dti


## Technologies Used
 
Python 3.x

### Python Libraries
- pandas - version 1.1.4
- matplotlib - version 3.5.1
- seaborn - version 0.11.2

## Assumptions
- funded_amnt_inv is already included in funded_amnt. Hence, funded_amnt_inv is ignored for the analysis
- Applicants with loan status as current are removed for the analysis as they are not clear indicators of defaulters or not. 


## Contact
Created by [@SathishKumarRamasamy] - feel free to contact me!
