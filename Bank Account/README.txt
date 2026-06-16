README – BankAccount Mini Project

Project Overview
This project implements a simple Bank Account system using Object-Oriented Programming in Python.
The program allows creating bank accounts, depositing money, withdrawing money, checking balances, and viewing transaction history.
Each account automatically generates a unique ID and creates a statement file to store all transactions.

Features

Create a new bank account with name, account type, and optional starting balance

Automatically generate a unique account ID

Create a transaction history file for each user

Deposit money

Withdraw money with balance validation

Retrieve current balance

Retrieve user ID, username, and account type

View full transaction history from the file

How the Program Works
When a BankAccount object is created, the constructor generates an account number and creates a text file named using this format:
<accountID><accountType><username>.txt
This file stores all transactions and account information.

The deposit and withdraw functions update the balance and write the transaction details into the file.
The user can also check their balance and read their full transaction history.

Files Created
Each account creates a text file that contains:

Account creation details

Deposits

Withdrawals

Updated balances

Failed withdrawal attempts

How to Test the Program
Create multiple BankAccount objects and perform different transactions such as deposits and withdrawals.
Print the balance and transaction history to verify that the program works correctly.

Example test actions include:

Creating two accounts

Depositing money

Withdrawing money

Attempting to withdraw more than the balance

Printing balances

Printing transaction history

Requirements

Python 3

No external libraries required

Purpose of the Project
This mini project helps practice:

Object-Oriented Programming

Constructors and class methods

File handling

Data storage

Basic banking logic