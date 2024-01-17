# Lending Club Case Study
> Detailed data analysis of driving factors that leads to loan default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
We are working for a consumer finance company which specialises in lending various types of loans to urban customers.
 When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Conclusions
- Univariate Analysis
- Factors having greater impact- 
   1. Higher interest rate,
   2. Longer repayment term 60 months
   3. Loan grade  D,E,F,G and loan Sub grade D2 to F5.
   4. Applicant addr state like AK,SD,NV,NE. 
   5. Purpose for loan like small bussiness,renewable energe and educational.
   6. Non zero Derogatory Public records
   7. Non zero Public bankruptcy records.
- Factors having smaller impact- 
   1. Higher installment
   2. Higher loan amount.
   3. Annual income , higher dti
   4. Loan issue month Dec and May
- Bivariate Analysis
   1.Purpose of loan and applicants addr state,higher charged off rate for  vacation role in AK,IA.
     moving expenses in moving.Home improvement and home expenses in NE,NJ.
   2.Purpose of loan and income group,small bussiness loans for medium and lowest income groups are riskier.Renewable loans for higher income groups are riskier.

## Technologies Used
- python
- matplotlib
- seaborn

