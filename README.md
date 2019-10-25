# Investigating Loan Data from Prosper


## Dataset

This dataset is a list of loans from Prosper with many characteris on each loan. There are 113,937 loans in the dataset with 81 features. Most variables are numeric or dates in nature, but some are texts like occupation and employment status.


## Summary of Findings

For this exploration, I looked into the borrower annual percentage rate (BorrowerAPR). I want to learn about what features in the dataset influences this rate.

Many relationships were uncovered in the exploration. Some of the relationships found for the main feature of interest (borrower APR) are:

- The loan amount and credit score variables strengthened each other. They are both negatively correlated with borrower APR.
- The income range has a clear effect on borrower APR with higher income ranges having lower borrower APR.
- If the income is not verifiable, a higher credit score is required to get the same borrower APR.
- Employment status influences borrower APR with more stable employment having lower overall borrower APR.
- It was interesting that the open credit lines, employment duration and home loan status didn't effect borrower APR much.

There were also some relationships between other features as per below:

- Home loan owners tend to fall in higher income ranges. This may be why having a home loan did not effect the BorrowerAPR as much as I thought it would.
- People with higher income are generally employed full time or self-employed.
- The income range can effect the loan amount. Lower income ranges do not usually have larger loans.


## Key Insights for Presentation

For the presentation, I focused on the key variables that influenced borrower APR the most. 

I started by introducing the borrower APR variable and it's ditribution. Following this, I moved on to the different variables that influenced borrower APR the most from my analysis. I started with the employment related variables I was most interested in.

The goal for this presentation is to highlight that from the data exploration, income range, income verifiable, credit score and loan amount influenced borrower APR the most and how each of them did that.

