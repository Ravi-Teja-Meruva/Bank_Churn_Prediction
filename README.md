# Bank_Churn_Prediction

## Problem Statement: 

Imagine you are working as one of the Data Scientists for a largest bank in the country who has overall portfolio of 2,25,000 customers. So, the director of customer management wants to know which customer segments are more likely to churn balances in the next quarter by atleast 50% considering current quarter.

## List of Hypothesis:

1.Based on demographics 

2.Based on customer behaviour with bank

3.Psychographic of the customers

## Data Collection/Extraction:

1.Customer:

- customer_id : unique id for each customer

- vintage : Association of the customer with the bank in number of days

- age : Age of customer

- gender : gender of customer

- dependents : Number of dependents

- occupation : Occupation of the customer

- city : city of customer

2.Transaction:

- current_balance : balance as of today
- current_month_credit : total credit amount current month
- current_month_debit : total debit amount current month
- current_month_balance : Average Balance of current month
- previous_month_end_balance : End of Month Balance of previous month
- previous_month_credit : total credit amount of previous month
- previous_month_debit : total debit amount of previous month 
- previous_month_balance : average balance of previous month
- average_monthly_balance_prevQ : average balance in previous quarter
- average_monthly_balance_prevQ2 : average balances in previous to previous quarter
- customer_nw_category : Net worth of customer(3:Low 2:Medium 1:High)

3.Bank Branch:

- branch_code
- last_transaction

