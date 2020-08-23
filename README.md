# (Prosper Loans)
## by (Abdullah Elsayed)


## Dataset

> Prosper is a peer-to-peer lending platform that aims to connect people who need money with those people who have the money to invest. In this data analysis project, I have explored the Prosper dataset, prepare it for analysis and used 'Pyplot and Seaborn' to create my visualization and communicate results.

> Prosper dataset contains 113937 Rows, And 81 Variable between 2005 and 2014 with data about Loans and Borrowers and investors
 


## Summary of Findings

>   - There are about 60000 Loan with category Debt Consolidation, While all ather categories under 10000 loan

    - 63% of the money goes into the debt conolidation
    
    - The Most Term of loan is 36 Month, There are 80133 Loan with This Term
    
    - There are about 75.4% Loans with term 36 Month and 23.1% with term 60 month, and 1.5% with term 12 Month
    
    - The interval of Borrower Rate is between 0.03% and 0.35, and we can't assume there are outliers
    
    - Most loan values range from 1000 to 35000 , but only a few people ask for loans above 20000
    
    - CA is highst state ask for loans, Then NY, FL, TX.
    
    - The Lowest states ask for loans is ND, ME, WY, IA
    
    - The majority of the loans were fully funded and a very small percentage of the loans were funded by more than 70% of their original value
    
    - The histogram shows that loans funded by more than 500 investor are outliers, and The most is funded by lower then 200 invstor. but The outliers here dosn't affect the analysis so i will keep it
    
    - the borrower who is employed has the highest stated monthly income and the borrower who is part-time has the lowest monthly income.
    
    - there is strange something that the borrower who is not-employed has stated monthly income bigger than the borrower who is part-time 
    
    - The most losses happen when prosper score is prefer to high risk

## Key Insights for Presentation

	- The most losses happen when prosper score is prefer to high risk.
	- ProsperScore of the loan categories is approximately the same, but it tells us that Personal loans, RV and Motorcycle is the highst risk. while household expenses is lowest risk.

## Prerequisites
	- Jupyter Notebook
	- Python 3
	- Python libraries: Pandas, Numpy, Matplotlib, Seaborn, missingno

## Run slide Deck From the following command : 
	- jupyter nbconvert prosperLoanData-Explonatory-part2 --to slides --template output-toggle.tpl --post serve



