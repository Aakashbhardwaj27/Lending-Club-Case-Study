# Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Analysis and Observations](#analysis-and-observations)
* [Further Analysis](#further-analysis)

## General Information
This project focuses on analyzing loan data from Lending Club to identify trends and patterns in loan performance. The aim is to understand the nature of loans, identify potential defaulters, and categorize loans into "good" and "bad" based on various factors.

### Background
Lending Club provides peer-to-peer loans, where borrowers receive loans directly from investors. The goal of this case study is to examine the data, detect any potential default risk, and categorize loans as good or bad based on factors like loan amount, interest rate, and annual income.

## Conclusions
- The loan amount distribution is right-skewed, with most borrowers seeking smaller loans.
- There is a positive correlation between loan amount and interest rate, indicating that higher loan amounts come with higher interest rates.
- Annual income plays a significant role in loan performance, with borrowers earning less tending to default more often.
- Loans with higher interest rates and larger loan amounts are more prone to default, while smaller, lower-interest loans tend to be less risky.

## Technologies Used
- Python - version 3.10
- pandas - version 1.3.3
- seaborn - version 0.11.2
- matplotlib - version 3.4.3
- scikit-learn - version 0.24.2

## Analysis and Observations

### Loan Amount Distribution
The distribution of loan amounts is right-skewed, indicating that a larger number of loans are for smaller amounts.

### Loan Status Distribution
We observed that most loans are either fully paid, current, or charged-off. This distribution helps in understanding the general loan lifecycle.

### Loan Amount vs Interest Rate
There is a positive correlation between loan amount and interest rate. Higher loan amounts typically come with higher interest rates, indicating greater risk.

### Annual Income vs Loan Status
Borrowers with lower annual income tend to default more, showing that income is an important factor in loan repayment capacity.

### Correlation Matrix
The correlation matrix revealed key relationships between numerical variables, such as the strong correlation between loan amount and interest rate.


## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Aakashbhardwaj27](https://github.com/Aakashbhardwaj27) - feel free to contact me!

