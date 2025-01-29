# Loan Default Risk in Consumer Finance

### Problem Understanding
This case study revolves around using Exploratory Data Analysis (EDA) to analyze loan applicants' data and determine factors that contribute to loan default. A finance company wants to minimize credit loss by identifying applicants who are at high risk of defaulting on their loans. By doing so, the company can make informed decisions regarding loan approvals, rejections, and terms (e.g., higher interest rates or reduced loan amounts for risky applicants).

### Business Problem Breakdown
The main risks involved in loan approval are:

- Risk of Loss of Business: If the company rejects a loan that could have been repaid, it loses out on business.
- Risk of Credit Loss: If the company approves a loan that the applicant is unlikely to repay, it will face financial loss due to default.
- To mitigate these risks, the company needs to understand which factors contribute to loan defaults. This will allow them to avoid lending to high-risk applicants.

### Loan Data Set and Loan Types
The loan data set includes information about applicants' profiles and the outcome of their loan application. Here are the possible outcomes:

- Fully Paid: The applicant has repaid the entire loan.
- Current: The applicant is still in the process of repaying the loan.
- Charged-off: The applicant has defaulted, i.e., not repaid the loan for an extended period.
- Rejected: The loan was denied, and there is no further transaction history.
  
The main focus for EDA will be on identifying defaulted applicants, as they are the primary concern for minimizing credit loss.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
### Risk Analytics in Banking
Risk analytics is a critical aspect of modern banking and financial services. The process of credit risk assessment involves evaluating the likelihood that a borrower will default on a loan. By using historical data and predictive modeling, banks can:
- Build risk profiles for applicants based on their financial history and other factors.
- Predict the likelihood of default and estimate potential financial losses.
- Adjust loan terms or interest rates for high-risk applicants to minimize credit loss.
Loan Dataset was used to solve this problem. It contains the complete loan data for all loans issued through the time period 2007 t0 2011

## Conclusions

The analysis shows that 82.9% of applicants successfully paid their loans, while 14.1% defaulted. Key factors influencing loan defaults include:
- Loan Grade: Loans with lower grades have higher default rates, highlighting the importance of grade in lending decisions.
- Income: Borrowers earning less than $40K exhibit higher default rates across all loan types. However, higher-income borrowers still default more frequently with larger loan amounts.
- Loan Amounts: Larger funded amounts correlate with higher default rates, especially among low-income borrowers.
- DTI Ratio: Higher DTI ratios are linked to higher default rates, with borrowers in the 20+ DTI range showing a complex pattern where a moderate number of open accounts reduces risk slightly.
- Interest Rates and Loan Term: Higher interest rates and longer loan terms increase the likelihood of default, while lower interest rates and shorter terms reduce it.
These insights suggest that lenders should prioritize loan grade, income stability, and DTI ratio when evaluating default risk, while also considering loan amount and term structure.


## Technologies Used
- anaconda
- Jupyter notebook
- itables
- numpy
- pandas 3.0
- matplotlib
- seaborn

## Acknowledgements
Thank you upgrade for providing this oppertunity to solve such a problem statement also lectures has helped us to solve this 

## Contact
Created by [@vkgupt11] - feel free to contact me!


