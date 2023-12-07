![image](https://thumbs.dreamstime.com/z/credit-card-companies-design-vector-illustration-most-popular-cards-isolated-white-background-124770411.jpg)


As a data science team in a credit card company, our goal is to develop risk models in order to 

measure the probability of a customer ceasing repayment of their balance. Your task is to build a 

classifier that predicts which customers will be unable to pay their balance for 2 months within the

next 12 months.
Data Dictionary
id: unique identifier of the account
• existing_score: the score of the existing machine learning model (you may use it as an input 
or for checking if your model performs better than the existing model)

• open_to_buy: the difference between the credit limit and the balance. If the customer does 
not have a credit card, it is NaN.

• months_since_first_loan_issued: number of months since the first loan was issued. If the 
customer has not taken any loans, it is NaN

• existing_credit_card_utilization: balance / credit limit * 100, e.g. 30 means that 30% of the 
credit limit is utilized. If the customer does not have a credit card already, it is NaN

• n_months_mortgage_loan_paid: number of months during which the balance of the 
account decreased. If the customer does not have a mortgage already, it is NaN
The file “y.csv” contains the following columns:

• id: unique identifier of the account

• label: 1 if the account did not pay their balance for 2 months during the next 12 months, 
otherwise 0.
