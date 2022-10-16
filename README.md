# Loan Prosper Exploration
## by Truong Quang Minh Tu


## Dataset

The dataset contains 113937 loans with 81 variables corresponding to each loan including loan amount, payment, interest rate. Most of the columns are numeric data (indicate loan, interest, fee amount...), categorical data (Occupation, Loan Status...) and ordinal data (CreditGrade, LoanStatus...).

The summary of dataset can be found here for more clarification in the field definition https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

The main findings are the relationship between variables that can correlate with the amount prosper loan and the amount proper loan loss

The main features of interest in the dataset is to find out what variables highly correlate with the 2 followings: 
- The amount prosper loan 
- The amount proper loan loss - The principal that remains uncollected after any recoveries.

The features will help support support my investigation is Prosper Loan Amount and the Prosper Loss Net, which are also the feature of interest. In order to make an investigation, the both could be explained by the other variables.

And the key findings are 
- The Loan Prosper Principal Outstanding will be best explained by variables: Term, Prosper Rating, Borrower Rate. These 3 variables have a positive relationship with the Loan Prosper Principal Outstanding as these three are higher in value, the Principal Outstanding will be higher. 
- The Net Loss on Prosper Loan has its mean = 0 then the recoveries (negative Net Loss on Prosper Loan) could set off the charged off loans which are loss (positive Net Loss on Prosper Loan).
- Out of the listing category, the listing category = 20 (1 - Wedding Loans) is the category that observes the most loan amount in the range 0-10000.

## Key Insights for Presentation

Summary for key findings:
- The Loan Prosper Principal Outstanding will be best explained by variables: Term, Prosper Rating, Borrower Rate. These 3 variables have a positive relationship with the Loan Prosper Principal Outstanding as these three are higher in value, the Principal Outstanding will be higher. 
- The Net Loss on Prosper Loan has its mean = 0 then the recoveries (negative Net Loss on Prosper Loan) could set off the charged off loans which are loss (positive Net Loss on Prosper Loan).
- Out of the listing category, the listing category = 20 (1 - Wedding Loans) is the category that observes the most loan amount in the range 0-10000.