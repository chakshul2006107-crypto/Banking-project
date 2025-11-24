# Console-Based Online Banking System

## Overview of the Project
This project is a Python-based console application designed to simulate the core functionalities of a banking system. It allows users to create accounts, perform financial transactions (deposits and withdrawals), and manage account details in a secure, menu-driven environment. The system utilizes in-memory data structures to demonstrate logic flow, data validation, and object management without the need for complex database setups.

## Features
* **Account Creation:** Automatically generates unique 5-digit account numbers and validates user details.
* **Secure Transactions:** Requires PIN verification for deposits, withdrawals, and balance checks.
* **Fund Management:** Real-time calculation of account balances with validation to prevent overdrafts.
* **Admin Dashboard:** specific "Display All Accounts" feature protected by an admin password (`pass123`) to view all registered users.
* **Account Maintenance:** Options to modify registered mobile numbers or close (delete) accounts permanently.
* **Data Integrity:** Prevents duplicate account numbers and ensures inputs (like PINs) adhere to specific formats.

## Technologies/Tools Used
* **Programming Language:** Python 3.x
* **Standard Libraries:** `random` (for account number generation)
* **IDE/Editor:** VS Code / PyCharm / IDLE (Any text editor works)
* **Platform:** Windows / MacOS / Linux (Cross-platform compatible)

## Steps to Install & Run the Project
1.  **Prerequisites:** Ensure you have Python installed on your system. You can check this by typing `python --version` in your terminal.
2.  **Download Code:** Clone this repository or download the `main.py` file.
3.  **Navigate to Directory:** Open your terminal/command prompt and navigate to the folder containing the file.
    ```bash
    cd path/to/your/project
    ```
4.  **Run the Application:** Execute the script using the Python command:
    ```bash
    python main.py
    ```

## Instructions for Testing
To verify the system works as expected, follow these test scenarios:

1.  **Create an Account:**
    * Select Option `1`.
    * Enter a name, valid mobile number, and initial deposit.
    * *Note down* the generated **Account Number** and your **PIN**.
2.  **Deposit Money:**
    * Select Option `2`.
    * Enter the Account Number and PIN from step 1.
    * Deposit an amount and check if the balance updates.
3.  **Withdraw Money:**
    * Select Option `3`.
    * Try withdrawing an amount *greater* than your balance (check for error).
    * Try withdrawing a valid amount (check for success).
4.  **Admin Access:**
    * Select Option `5` (All Account Holder List).
    * Enter the password: `pass123`.
    * Verify that your account details appear in the list.
