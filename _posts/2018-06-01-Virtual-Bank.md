---
title: Virtual Bank
layout: post
date_range: June 2018 - August 2018
post-image: 
description: A command-line banking application that allows you to deposit, withdraw, and write checks.

---

# About Project
Prompt
```
Design and implement a hierarchy inheritance system of banking, which includes Savings and Checking Accounts of a customer. Inheritance and virtual funtions must be used and applied, otherwise there is no credit.

The following features must be incorporated:
	1. The account must have an ID and customer's full name and his/her	social security number.
	2. General types of banking transactions for both accounts, Checking and Savings: 
		- withdraw
		- deposit
		- calculate interest (based on the current balance, and if it was not modified, there will be no new interest)
		- figure out the balance
		- transfer funds (between the two accounts, from Checking to Savings and vice versa).
	3. Savings restrictions:
		- Become inactive if balance falls below $25 and, under such situation, no more withdrawals may be allowed.
		- A $1 charge for each transfer fund (to Checking account), with the first transfer being free.
		- The monthly interest rate is 3.75%.
	4. Checking restrictions:
		- A monthly service charge is $5 (automatically charged when Checking account was opened).
		- A $0.10 charge for each written check, with the first check free.
		- A $15 charge for each bounced check (not enough funds).
		- The monthly interest rate is 2.5%.
```