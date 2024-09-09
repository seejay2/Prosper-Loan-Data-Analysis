# Prosper-Loan-Data-Analysis
Udacity Prosper Loan Data Project

## Overview
This project involves analyzing a dataset of loans to uncover key insights into financial variables, borrower characteristics, and loan statuses. The analysis utilizes Python's data manipulation and visualization libraries, such as pandas and seaborn, to explore various aspects of the dataset. Three different types of visualizations — univariate, bivariate, and multivariate — are employed to achieve the overall goal of understanding patterns and relationships in the data.

## Objectives
The main objectives of this project are to:

* Understand the Distribution of Credit Scores: Analyze the distribution of borrowers' credit scores to understand the general creditworthiness of the loan applicants.

* Examine the Relationship Between Credit Score and Loan Amount: Investigate how the credit score of borrowers affects the loan amount they receive, which can provide insights into lending patterns.

* Explore Interactions Among Multiple Financial Variables: Use a multivariate analysis to examine how different financial variables, such as BorrowerAPR, CreditScoreRangeLower, LoanOriginalAmount, and DebtToIncomeRatio, interact with each other.

## Data Description
The dataset contains various features related to loans, including but not limited to:

* CreditScoreRangeLower The lower bound of the borrower's credit score range.
* LoanOriginalAmount The original loan amount approved for the borrower.
* BorrowerAPR The annual percentage rate of the loan, indicating the cost of borrowing.
* DebtToIncomeRatio: A ratio indicating the borrower's total debt payments to their income.
* ProsperRating (Alpha): A categorical rating assigned to the borrower based on their credit risk.
* LoanStatus: The current status of the loan (e.g., Current, Completed, Defaulted).

## Summary of Findings

* Distribution of Credit Scores: Most borrowers fall within a specific credit score range, indicating a concentration of applicants with moderate credit risk. This distribution helps in understanding the general creditworthiness of borrowers in the dataset.

* Credit Score vs. Loan Amount Relationship: Borrowers with higher credit scores tend to receive larger loan amounts, highlighting that lenders are more inclined to approve larger loans to individuals with lower credit risk. There is also variability in loan amounts for different credit scores, with some outliers indicating unique cases.

* Interactions Among Financial Variables: The pair plot reveals several patterns and relationships among key financial variables. For instance, BorrowerAPR and CreditScoreRangeLower show a negative relationship, indicating that higher credit scores generally result in lower APRs. The plot also shows how different Prosper Ratings influence these variables, with distinct clusters for different ratings.
