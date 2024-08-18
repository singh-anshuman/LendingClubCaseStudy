# Lending Club Case Study
> Lending Club is a consumer finance company which specialises in lending various types of loans to urban customers. This company needs to **identify key driving factors leading to the loans getting charged off**.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

## General Information
### Problem Statement
There are 2 types of risks associated with Lending Club's decision of approving or rejecting a customer's loan application.

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

### Business Objective
To identify strong driving factors which are potential indicators of customers defaulting and the loan getting charged off. These factors will be used to identify risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.


### Data Set
* A csv containing data about previous loan applicants have been given (including whether they defaulted or not) along with data dictionary describing the columns.
* There are 39,717 records in the data set with each record containing 111 columns.
* The data set also contains information about whether these applications defaulted or not.


## Conclusions
After doing a thorough cleaning of the data set and employing Segmented Univariaate and Bivariate analysis methods, results mentioned below were observed.

### Key Drivers Indicating Loan Default

- **Debt to Income Ratio (dti)** - Customers with high debt to income (dti) ratio are more likely to get default on the loan.
- **Delinquencies (delinq_2yrs)** - A customer with a record of delinquencies in the past is more likely on default on the loan.
- **Interest Rate (interest_rate)** - Loans where interest is higher are relatively more likely to get charged-off.
- **Revolving line utilization % (revol_util)** - A customer with higher % utilization of revolving credit line is more likely on default on the loan.
- **Loan Term (term)** - A 36-month term loan is more likely to get charged off than a 60-month term loan.


## Technologies Used
- Pandas - version 2.1.4
- Matplotlib - version 2.0
- Seaborn - version 3.8.0

## Contact
Created by [@singh-anshuman] and Sourabh Maheshwari - feel free to contact us!