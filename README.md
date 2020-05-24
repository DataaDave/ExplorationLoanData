# Loan Data Exploration
## by David Bohnhoff


## Dataset

The data consists of around 114,000 loans with over 80 variables for each loan. These variables include different ratings, income range, employment status and for example if hte borrower is a homeowner or not. The data can be found [here](https://github.com/DataaDave/ExplorationLoanData/blob/master/data/prosperLoanData.zip) with explanation of the column names available [here](https://github.com/DataaDave/ExplorationLoanData/blob/master/data/Prosper%20Loan%20Data%20-%20Variable%20Definitions.xlsx)


## Summary of Findings

During the exploration process I found that BorrowerAPR (interest the borrower has to pay) has a very high negative correlation with ProsperRating (A Rating assigned with categories from HR(high risk / worst) over E, D, C, B, A till AA (best)). There is also a negative correaltion with the Income Range of the borrower. Suprisingly higher loan amounts on average have lower BorrowerAPR than smaller loan amounts. This is explainable via the ProsperRating as well since high loan amounts are only available for borrower in the good ProsperRating categories.
Beside the main variables I also looked into the fact if a homeowner gets better loan conditions. The BorrowerAPR is slightly lower while loan amounts are higher for homeowner. The employment status of the borrower also has an impact on the Borrower APR with unemployed borrower having higher Borrower APR than employed borrower. The term (duration of the loan) had no impact on the BorrowerAPR but longer loan durations correalted with higher loan amounts.


## Key Insights for Presentation

For the presentation I mainly focused on the Borrower APR and concluded that the ProsperRating has the biggest influence on it.
I started with the distribution of the borrower APR. Showing next the correlation between Borrower APR vs. Loan Amount and followed up with BorrowerAPR vs ProsperRating. Finnaly I combined the two plots in a multifaceted heatmap plot showing the distribution of the BorrowerAPR vs Loan Amount for the different ProsperRatings.
