# Explanatory Data Analysis for Prosper Loan Data
## by Ismail Omodara


## Dataset

The dataset was gotten from [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), Prosper Marketplace (a San Francisco based company in teh peer-to-peer lending industry). 
The original dataset consisted of about 113,937 entries with 81 unique variables. 
For the purpose of focused analysis, we picked14 out of the 81 unique variables and 
performed data wrangling to clean up entries which resulted in us having to work with 
a dataset of 95,169 entries and 14 unique features.


## Summary of Findings

During the exploration, I found the relationship between the outcome of a loan
and the historical representation (ProsperScore). There exist a relationship
between the level of risk of the loan and the possible outcome.

Also found out that borrower's tend to request for more time (Term) in other to
be able to complete their repayment.


## Key Insights for Presentation

In the presetnation, I focused on finding the influence of ProsperScore (and Borrower's Rate)
on the outcome of a loan (LoanStatus).I started with a representation for LoanStatus using a
bar chart, then followed it with another with a relationship between two of our variable of 
interest.


Then I explored relationships among these variables with using clustered bar chart and box plot
to show how one feature affects another and possible outcome of the loan in general.