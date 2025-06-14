# Expense-Tracker
IIT G Python

PROJECT WRITE-UP
Title: Personal Expense Tracker

BY: Samarth Arora


1. Problem Statement:
In today’s fast-paced world, managing personal finances is crucial. Individuals often struggle to track where their money goes. This project aims to build a Personal Expense Tracker that allows users to log daily expenses, categorize them, and monitor spending against a monthly budget. The system will also support data persistence through file storage.

2. Objectives:
Design and implement a CLI-based expense tracker.


Allow users to:


Add and categorize expenses.


View recorded expenses.


Set and monitor monthly budgets.


Save and load data using file handling.


Provide a user-friendly, menu-driven interface.



3. Modules Implemented:
Add Expense:
 Collects date, category, amount, and description; stores them in a dictionary and appends it to a list.


View Expenses:
 Displays a list of all recorded expenses with validations for missing fields.


Set and Track Budget:
 Allows the user to input a monthly budget and tracks remaining or exceeded amounts.


Save & Load Functionality:
 Uses CSV file handling to save and retrieve expenses.


Interactive Menu:
 Provides a text-based menu to navigate the above features.



4. Tools Used:
Python 3.10+


Built-in libraries: csv, os

