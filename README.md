# Bike Sharing Assignment
> View file: https://nbviewer.org/github/sonal-jatav/LendingClubCaseStudy/blob/main/Sonal_Jatav_Lending_club_case_study.ipynb

The project is intended to derive variables that have a role in identifying factors that prevail in loan defaulter's data


## Table of Contents
* [Overview](#Overview)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#Contributors)

****

## Overview

1. Data cleaning - remove outliers, null values, fix data types
2. Data Analysis - Univariate, Bivariate, Multivariate
3. Visualise results
4. Conclusion


## Technologies Used
- Python - v3.11.5
- Python Libraries
  - pandas - v2.2.2
  - numpy - v1.26.4
  - plotly - v5.22.0
  - matplotlib - v3.9.0
  - seaborn - v0.13.2
  - statsmodels - v0.14.2
  - scikit-learn - v1.5.0
- Jupyter Notebook - v7.0.8

## Conclusions
- **Univariate Analysis**
1. Loan Amount: Most loans are small to moderate amounts with a few large loans.
2. Interest Rate: Interest rates vary, but there might be common rates around certain values.
3. Annual Income: Most borrowers have moderate incomes; a few have very high incomes.
4. Debt-to-Income Ratio: Most borrowers have a manageable Debt To Income ratio, but some might have higher values indicating more debt.
5. Term: A significant proportion of loans are of term 36months
6. Public record bankruptcies: A very small percentage of loan defaulters have filed bankruptcies.
7. Derogatory public records: A very small percentage of loan defaulters have derogatory public records.
8. Majority of the Charged off loans belong to customers with employment length around 10 and above years
9. Majority of the Charged off loans belong to customers who took loan for purpose of another debt consolidation
10. Majority of the Charged off loans belong to customers who live in a rented place and second to it who already have mortgage on their homes
11. 

- **Bivariate Analysis**
1. Interest Rate: Higher interest rates correlate with a higher risk of loan default.
2. Length of Employment: Stable, long-term employment is associated with better loan repayment, though it's not a strong standalone predictor.
3. Annual Income Groups: Higher annual incomes (above 58k) are associated with a higher likelihood of fully repaying loans. Lower income groups (3k-31k) show a higher risk of default, suggesting that income level is an important factor in assessing loan repayment capability.
4. Verification Status: Verified income and employment significantly reduce the risk of loan default.
5. Higher Grades (A, B): Likely to have fewer charged-off loans due to lower risk.
6. Moderate Grades (C, D): Higher likelihood of charged-off loans compared to higher grades.
7. Lower Grades (E, F, G): Higher risk categories with more charged-off loans.
8. Higher Interest Rates: Charged Off loans are more concentrated at higher interest rates, suggesting that borrowers with higher interest rates are at a greater risk of default.
9. Loan Amounts: There is no clear differentiation in loan amounts between Fully Paid and Charged Off loans, indicating that loan amount alone may not be a strong predictor of default.
10. Combined Effect: While higher loan amounts are generally associated with higher interest rates, the risk of default appears to be more closely related to the interest rate rather than the loan amount.
11. Loan amount vs Public Record of Bankruptcies is inconclusive to derive a loan amount range that is relative to bankruptcies
12. Maximum number of loan defaulters(Charged Off loan_status) were in the following ranges:¶
  - Interest Rate - 11.26 - 16.32
  - Annual Income - 36.3k - 71.67k
  - Debt to Income Ratio - 9.18 - 19.40
13. Highest number loan defaulters(Charged Off loan_status) are as follows:
  - Requested loan during the month - December
  - Requested loan during the year - 2011
14. Highest number loan defaulters(Charged Off loan_status) are as follows:
  - Requested loan for Purpose - Debt Consolidation
  - Requested loan from State - CA - California
15. Highest number loan defaulters(Charged Off loan_status) are as follows:
  - 9%-17% Interest rates
  - 2-10 open credit lines
  - 2-37 total credit lines currently in the borrower's credit file
  - 31k - 85k Annual Income
  - 5k - 10k Loan Amount

- **Multivariate Analysis**
1. Higher interest rates, high DTI ratios, and high revolving utilization are key indicators of higher default risk.
2. Lower annual income may also contribute to higher default risk.
3. Interest Rate (int_rate): Higher rates are associated with higher default risk.
4. Annual Income (annual_inc): Lower incomes are linked to higher default rates.
5. Debt-to-Income Ratio (dti): Higher DTI ratios are indicative of higher default risk.
6. Revolving Utilization (revol_util): Higher utilization rates correlate with higher default risk.
7. Public Record Bankruptcies (pub_rec_bankruptcies): History of bankruptcies increases default likelihood.


---------------------------------------------------------------------------------------------------------
## Contributor
Sonal Jatav [@sonal-jatav]
