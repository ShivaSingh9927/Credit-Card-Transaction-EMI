# Credit-Card-Transaction-EMI
This is competition problem in which unfortunately we didn't got the top 3 position but me and mine team have got overall rank of 7. Please note that at some places you might not find proper commenting or warning, bcz we have did this code in a fixed time-span. You can further explore more features and improve its accuracy. Please refer to the pdf that i have upoaded in the repository to get a complete idea of problem statement.

## Introduction
Banks offer EMI facility to their Credit Card customers. Customers can use this facility to break down 
their big-ticket purchases into smaller, more manageable monthly repayments, all the while avoiding 
paying revolve interest. 
EMIs are offered to customers at various stages:
1. Point of sale: EMI conversion can be done at time of purchase. Banks have tie ups with a 
selected set of merchants (both online and offline) where this facility is offered
2. Post transaction: Customers can reach out to the Bank for a period of 30-60 days post the 
transaction and convert the same into EMI
3. Balance on EMI: Banks offer this plan to a select set of customers who can convert their 
entire outstanding into EMI
Credit Card issuers spend a significant amount of time and effort into ensuring that a high 
percentage of spends get converted into EMI. This enables the Banks to secure a good revenue 
stream – including processing fees, interest, and foreclosure penalties. Additionally, Banks don’t 
offer reward points on transactions that have been converted to EMI.

# Problem statement
Bank A has a large base of savings account customers who have been cross sold Credit Cards. Bank A 
launched post transaction EMI as a proposition on their Credit Cards. However, conversion rates 
through digital campaigns were low. So, Bank A set up a call center where agents would call 
customers and sell post transaction EMI. 
However, Bank A soon realized that while this led to an increase in conversion rates of post 
transaction EMI, the cost too was on the higher side. Bank A then decided to only call customers 
who were more likely to convert their transactions into EMIs. This would enable the Bank to have 
fewer agents dedicated to EMI calling, thereby reducing the cost.
Your objective is to help the Bank prioritize its Credit Card transactions for EMI calling.

# Datasets
You have been provided with a random sample of 50,000 Credit Card transactions 
“case_study_devdata.zip”, along with a flag (target_variable) – henceforth known as “development 
data”. Transactions that have been converted to EMI have target_variable = 1. You have also been 
provided with several independent variables. These include transaction attributes (amount, 
merchant etc.), card attributes (credit limit, product type etc.), previous history on the Card (spends 
on the card in the last few months, previous EMI conversion history etc.), savings account attributes 
(balances that the customer maintains in their savings account) and bureau attributes (kind of 
products the customer holds on the bureau). 
You have also been provided with another random sample of 30,000 Credit Card transactions 
“case_study_validation.zip” with the same set of input variables, but without target_variable. This 
will be referred to going forward as “validation data”.
Lastly, you have been provided with the data dictionary.
