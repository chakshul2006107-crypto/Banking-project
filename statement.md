# Project Statement

## Problem Statement
In traditional banking scenarios or manual record-keeping systems, managing customer data and transactions is prone to human error. Calculation mistakes, lost records, and slow processing times are common issues. There is a need for a digitized, automated solution that can handle basic banking operations instantly, ensuring accurate calculations and secure access to account information without the need for physical ledgers.

## Scope of the Project
This project aims to build a functional prototype of a banking system using Python. 

**In Scope:**
* User registration and unique ID generation.
* Arithmetic processing for deposits and withdrawals.
* Security validation (PIN and Password checks).
* Console-based user interface for interaction.
* In-memory data storage (data exists as long as the program runs).

**Out of Scope:**
* Persistent database storage (SQL/Files) – data resets when the application closes.
* Graphical User Interface (GUI).
* Network connectivity or real-time money transfer between different banks.

## Target Users
* **Bank Clerks/Admins:** Who need to view lists of all accounts and manage customer data.
* **Customers:** Who wish to create accounts, check balances, and perform transactions.
* **Students/Developers:** Users looking to understand the logic behind banking algorithms and Python data structures.

## High-Level Features
1.  **User Authentication:** The system uses a PIN-based authentication mechanism for users and a password-based mechanism for administrators to ensure unauthorized users cannot access sensitive financial data.
2.  **Transaction Processing Engine:** A robust logic block that handles additions and deductions to the account balance, ensuring that account balances never drop below zero due to invalid withdrawals.
3.  **Dynamic Account Management:** The ability to dynamically add new users to the dictionary structure, modify their details, or remove them entirely from the system memory.
