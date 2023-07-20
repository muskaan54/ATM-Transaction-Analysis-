# ATM Transaction Analysis using Power BI

## Introduction

Wisabi Bank is a prominent financial institution in Nigeria with branches in Lagos, Kano, Rivers State, Enugu, and FCT Abuja. As part of its commitment to improving customer experience and optimizing its operations, Wisabi Bank has conducted a data analytics project to analyze its ATM transactions data. This project aims to gain insights into various aspects related to ATM transactions using Power BI.

## Dataset Overview

The dataset used for analysis consists of several tables:

1. **Transaction Fact Table**:
   - TransactionID: Unique identifier for each transaction in the database.
   - TransactionStartDatetime: Datetime when the transaction started.
   - TransactionEndDatetime: Datetime when the transaction was completed.
   - Cardholder ID: Unique identifier for the cardholder performing the transaction.
   - Location ID: Unique identifier for the location of the ATM where the transaction occurred.
   - Transaction Type ID: Unique identifier for the type of transaction that was performed (e.g., withdrawal, savings, balance enquiry, transfer).
   - Transaction Amount: Amount of money involved in the transaction.

2. **Location Dimension Table**:
   - Location ID: Unique identifier for the ATM location.
   - Location Name: Name of the bank branch where the ATM is located.
   - No of ATMs: Number of ATMs in that location.
   - City: City in which the ATM is located.
   - State: State in which the ATM is located.
   - Country: Country in which the ATM is located.

3. **Customer Dimension Table**:
   - Cardholder ID: Unique identifier for the cardholder.
   - First Name: First name of the cardholder.
   - Last Name: Last name of the cardholder.
   - Gender: Gender of the cardholder (e.g., male, female, other).
   - ATM ID: Unique identifier for the ATM that the cardholder uses.
   - Age: Age of the cardholder.
   - Occupation: Occupation of the cardholder.
   - Account Type: Type of account that the cardholder has (e.g., savings, checking, etc.).
   - Is Wisabi: Boolean flag that indicates whether the cardholder is a customer of Wisabi Bank or another bank.

4. **Transaction Type Dimension Table**:
   - TransactionTypeID: Unique identifier for the transaction type (e.g., withdrawal, savings, balance enquiry, transfer).
   - Transaction Type: Name of the transaction type (e.g., "withdrawal", "savings", "balance enquiry", "transfer").

5. **Hour Dimension Table**:
   - Hours: Hour of the day (0-23).
   - Hour Start Time: Time at which the hour begins (e.g., 12:00 AM for hour 0).
   - Hour End Time: Time at which the hour ends (e.g., 1:00 AM for hour 0).

6. **Calendar Dimension Table**:
   - Date: Date in YYYY-MM-DD format.
   - Quarter: Quarter of the year in which the date falls (e.g., Q1 for January-March, Q2 for April-June, etc.).
   - Month: Month in which the date falls (e.g., 1 for January, 2 for February, etc.).
   - Month Name: Name of the month (e.g., January, February, etc.).
   - Day: Day of the week in which the date falls (e.g., Monday, Tuesday, etc.).
   - Is Holiday: Boolean flag that indicates whether the date is a public holiday.
   - Day Name: Name of the day (e.g., Monday, Tuesday, etc.).
   - Week of Year: Week of the year (From 1 to 54).
   - Year: Year (e.g., 2022).
   - Start of Month: Start of the month for each date value.

## Business Problems

The project aims to answer several business problem questions related to ATM transactions data:

1. What is the average transaction amount by location and transaction type?
2. Which ATM location has the highest number of transactions per day, and at what time of the day do the transactions occur most frequently?
3. Which age group has the highest number of transactions, and which transaction type do they usually perform?
4. What is the trend of transaction volume and transaction amount over time, and are there any seasonal trends or patterns?
5. What is the most common transaction type, and how does it vary by location and customer type (Wisabi customer vs. non-Wisabi customer)?
6. What is the average transaction amount and transaction frequency per customer by occupation and age group?
7. What is the percentage of transactions that are withdrawals, savings, balance enquiries, and transfers, and how does it vary by location and time of day?
8. What is the distribution of transaction amounts and transaction frequency, and are there any outliers?
9. Which ATM locations have the highest and lowest utilization rates, and what factors contribute to this utilization rate?
10. What is the average transaction time by location, transaction type, and time of day, and how does it vary by customer type and occupation?

## Scope

The data analytics project involves analyzing the ATM transactions data, including data cleaning, transformation, and visualization using Power BI. The analysis covers various aspects of transaction data, customer demographics, transaction types, and ATM locations. The insights gained from this analysis will help Wisabi Bank make data-driven decisions to improve customer experience and optimize its operations.

## Data Source

The dataset used for this analysis has been obtained from Kaggle and is provided as an Excel worksheet.

## Power BI Dashboard

The results of the analysis and insights will be presented in an interactive Power BI dashboard, allowing stakeholders to explore and visualize the data effectively.
