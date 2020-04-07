# Data-Exploration-Loan-Data-from-Prosper
## Loan Characteristics base on the Annual Percentage Rate
>Dataset:
This dataset contains 113,917 rows of loans brought based on their employment status and the Annaual Percentage Rate.
It has total of 81 columns and I reduced the data to contain only the neccessary 5 columns to get the characteristics of the data.I removed the null rows in the dataset for the sake of exploration to provide more reliable data

You can download the dataset [here]( https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000)

## Summary of findings
>I took only 5 columns

* `LoanOriginalAmount` : The origination amount of the loan. 
*   `BorrowerAPR` : The Borrower's Annual Percentage Rate (APR) for the loan.
*   `StatedMonthlyIncome` : The monthly income the borrower stated at the time the listing was created

*   `Term` : The length of the loan expressed in months.

*   `ProsperRating (Alpha)` : The Prosper Rating assigned at the time the listing was created between AA - HR.  Applicable for loans originated after July 2009.
*   `Employment Status` : The employment status of the borrower at the time they posted the listing.

1.   I found out that `BorrowerAPR` is negatively correlated with `LoanOriginalAmount`.
2.   I found that the `LoanOriginalAmount` is positively correlated with the `StatedMonthlyIncome`
3. There is an interaction with `LoanOriginalAmount` and `Term`

## Conclusions
* Majority of the loan propotion have in the following order
  C > B > A
* Majority of Loan Borrowed are in employed category
* 36 Month term loans are the most frequent one followed by 60 months
* Borrowers Annual Percentage Rate is has impact on the Loan terms   
