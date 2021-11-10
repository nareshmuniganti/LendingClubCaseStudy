# Lending Club Case Study
> Lending Club Case Study is to identify the driving factors which influence the loan applicants defaulting the loan payments. This info can be utilized for risk assesment and cutting down the credit loss for the company.


## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#Libraries-used)
* [Conclusions](#conclusions)


## General Information
- Understanding of risk analytics in banking and financial services using Exploratory Data Analytics and use it to minimise the risk of losing money while lending to customers.
- Dataset used: Loan.csv which has information about past loan applicants and whether they ‘defaulted’ or not. 
- Using EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## Conclusions
- Univariate Analysis Inferences:
    - This indicates that the loan amount for most applications is between 5k to 10K
    - More loan applicants tend to go for 36 months term compared to 60 months
    - Most of the appliations have around 200 to 400 as the monthly installment
    - For most applications the interest rate is around 10% to 14%
    - For majority of the applications the DTI is around 10 to 18
    - We observe that more number of cutomer loan application have status as "Not Verified"
    - More number of loan applications belong to "B" Grade
    - More number of loan applications belong to "A4" Sub-Grade
    - More applications belong to applicants with 10+ years of employement
    - Most loan applicants stay in rented properties followed by applicants who pay mortgage.
    - Debt consolidation and credit card card repayment is major purpose of Loan
    - Maximum customers do not have any bankruptcies filed
    - Maximum Loans are issued in the month of December 2011
    - Maximum loan applications are from CA state
- Segemented Univariate Analysis Inferences:
    - People tend to default the loans whenever the interest rate is higher comparing the above plots
    - Looking at the above graph, we can say that people with lower incomes tend to default the loans and higher income customer generally pay off the loans.
    - Higher income applicants tend to fully pay off the loans
    - Loan applications are more for 36 months compared to 60 months. 36 months loans are more likely to get paid off compared to the 60 month loans.
    - Loan applications with higher installements tend to default compared to the lower installments.Also, indicates that there could be some outliers in installment column
    - Loan applications with Grade "B" seems to default more compared to other grades
    - Loan applicants with rented properties seems to default loans compared to other home ownership categories
    - Loan applicants who default the loan, the verification status is "Not Verified". May be the applications are not verified thoroughly.
    - Loan applicants who default seem to have a slighly higher DTI compared to the fully paid applicants
    - Loan applicants who default seem to have no record of bankruptcy
- Bivariate Analysis Inferences:
    - Maximum Loan applicant who default have higher loan amount and purpose seems to be 'small business'
    - Maximum Loan applicants belonging to charged off group have higher loan amounts and have interest rates too.
    - Maximum Loan applicant from charged off group belong to grade "F" and their loan amount also high
    - Maximum Loan applicants from charged off group have higher loan amount and belong to +10 Years of employment length category
    - Maximum applicants from charged off group have high loan and more bankruptcies records on their name
    - Maximum applicants from charged off group have higher loan amount and their homeownership details are specified as "Other"
    - Maximum applicants from charged off group have higher loan amount and their verification status seems to "verified"
    - Maximum applicants from charged off group have higher loan amount and their loan term is high
    - Maximum applicants from charged off group with higher DTI have mortage
    - Maximum applicants from charged off group have slightly higher DTI for both 36 & 60 months loan term compared to the fully paid loan applications.
    - Maximum applicants from charged off group with higher DTI seems to belong to higher interest rate segment
    - Maximum applicants from charged off group with higher DTI belong to either 'C' or 'E' grades
    - Maximum applicants from charged off group with higher DTI seems to have verification status as "Verified"
    - Maximum applicants from charged off group with higher DTI belong to "credit card" payments
    - Maximum applicants from charged off group with higher DTI have 1 bankruptcy record
    - Maximum applicants from charged off group have higher interest rate and purpose seems to be 'house'


## Technologies/Libraries Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn


## Contact
Created by [nareshmuniganti] & [Sandipan3202] - feel free to contact us!