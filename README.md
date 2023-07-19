# ATM-Transaction-Analysis-Power BI
## Introduction-&nbsp; 	
Wisabi Bank is a leading financial institution in Nigeria, headquartered in Lagos with branches in Kano, 
Rivers State, Enugu, and FCT Abuja. Wisabi Bank provides a wide range of financial services to its customers, 
including savings accounts, current accounts, loans, and investments. As part of its commitment to improving 
customer experience and optimizing its operations, Wisabi Bank has engaged you as an external consultant to conduct
 a data analytics project to analyse its ATM transactions data.

### DATASET - 
Data has been taken from kaggle. It is attached as an excel worksheet above.

### DATASET OVERVIEW 
The dataset has various tables, the description is given below:

## Transaction fact table 
TransactionID- &nbsp; Unique identifier for each transaction in the database

TransactionStartDatetime-	&nbsp;    Datetime when the transaction started

TransactionEndDatetime-	&nbsp;      Datetime when the transaction was completed

Cardholder ID-&nbsp;  Unique identifier for the cardholder performing the transaction

Location ID-     &nbsp;         	  Unique identifier for the location of the ATM where the transaction occurred

Transaction Type ID-	 &nbsp;         Unique identifier for the type of transaction that was performed (e.g., withdrawal, savings, balance enquiry, transfer)


Transaction Amount-	 &nbsp;         Amount of money involved in the transaction

## Location dimention table 
Location ID- &nbsp; Unique identifier for the ATM location

Location Name- &nbsp; Name of the bank branch where the ATM is located

No of ATMs- &nbsp; Number of ATMs

City-&nbsp; City in which the ATM is located

State-&nbsp;	State in which the ATM is located

Country-&nbsp; Country in which the ATM is located

## Customer dimention table 
Cardholder ID- &nbsp; Unique identifier for the cardholder

First Name-	&nbsp; First name of the cardholder

Last Name-	&nbsp; Last name of the cardholder

Gender-	&nbsp; Gender of the cardholder (e.g., male, female, other)

ATM ID-	&nbsp; Unique identifier for the ATM that the cardholder uses

Age-	&nbsp; Age of the cardholder

Occupation-	&nbsp; Occupation of the cardholder

Account Type-	&nbsp; Type of account that the cardholder has (e.g., savings, checking, etc.)

Is Wisabi-	&nbsp; Boolean flag that indicates whether the cardholder is a customer of Wisabi Bank or another bank

## Transaction type dimention table 
TransactionTypeID-&nbsp;	Unique identifier for the transaction type (e.g., 1 for withdrawal, 2 for savings, 3 for balance enquiry, 4 for transfer)

Transaction Type- &nbsp;	Name of the transaction type (e.g., "withdrawal", "savings", "balance enquiry", "transfer")

## Hour dimention table 
Hours-&nbsp; 	Hour of the day (0-23)

Hour Start Time-&nbsp; 	Time at which the hour begins (e.g., 12:00 AM for hour 0)

Hour End Time-&nbsp; 	Time at which the hour ends (e.g., 1:00 AM for hour 0)


## Calender dimention table 
Date-&nbsp; 		Date in YYYY-MM-DD format

Quarter-&nbsp; 		Quarter of the year in which the date falls (e.g., Q1 for January-March, Q2 for April-June, etc.)

Month-&nbsp; 	Month in which the date falls (e.g., 1 for January, 2 for February, etc.)

Month Name-&nbsp; 		Name of Month (E.g January, February, etc.)

Day-&nbsp; 		Day of the week in which the date falls (e.g., Monday, Tuesday, etc.)

Is Holiday-&nbsp; 		Boolean flag that indicates whether the date is a public holiday

Day Name-&nbsp; 		Name of Day (E.g Monday, Tuesday, etc.)

Week of Year-&nbsp; 		Week of Year (From 1 to 54)

Year-&nbsp; 		Year (2022)

Start of Month-&nbsp; 		Start of Month for each date value


## Business Problems
Wisabi Bank wants to answer several business problem questions related to its ATM transactions data, which include:
i.	What is the average transaction amount by location and transaction type?

ii.	Which ATM location has the highest number of transactions per day, and at what time of the day do the transactions occur most frequently?

iii.	Which age group has the highest number of transactions, and which transaction type do they usually perform?

iv.	What is the trend of transaction volume and transaction amount over time, and are there any seasonal trends or patterns?

v.	What is the most common transaction type, and how does it vary by location and customer type (Wisabi customer vs. non-Wisabi customer)?

vi.	What is the average transaction amount and transaction frequency per customer by occupation and age group?

vii.	What is the percentage of transactions that are withdrawals, savings, balance enquiries, and transfers, and how does it vary by location and time of day?

viii.	What is the distribution of transaction amounts and transaction frequency, and are there any outliers?

ix.	Which ATM locations have the highest and lowest utilization rates, and what factors contribute to this utilization rate?

x.	What is the average transaction time by location, transaction type, and time of day, and how does it vary by customer type and occupation?

## Scope
The data analytics project involves analyzing the ATM transactions data, which includes the Transactions
fact table, Location dimension table, Customers Dimension table, Transaction Type Dimension Table, Hour dimension
 table, and Calendar dimension. The analysis involves data cleaning, data transformation, and data
 visualization using Power BI.









