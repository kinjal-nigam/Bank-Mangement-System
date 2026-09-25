# Banking System - Mini Project

## Project Overview

The Banking System is a Python-based mini project that simulates basic banking operations. It allows users to create an account, log in securely using an account number and PIN, and perform common banking activities through a menu-driven application.

## Main Features

- **Create Account** - Enter name and phone number, then create a 4-digit PIN.
- **Login** - Log in using the account number and PIN (up to 3 attempts).
- **Check Balance** - Display the current account balance.
- **Deposit Money** - Enter an amount and add it to the balance.
- **Withdraw Money** - Enter an amount, check the balance and deduct the amount.
- **Transfer Money** - Enter the receiver's account number and transfer money between accounts.
- **Transaction History** - Display all deposits, withdrawals and transfers with date and time.
- **Change PIN** - Enter the old PIN, then enter and confirm the new PIN.
- **Logout** - End the current session and return to the main menu.

## Python Concepts Used

- Variables and Data Types
- Conditional Statements
- Loops
- Functions
- Lists and Dictionaries
- String Operations
- Modules

## Modules Used

| Module     | Purpose                                            |
|------------|----------------------------------------------------|
| `random`   | Generates unique 10-digit account numbers          |
| `datetime` | Records the date and time of every transaction     |

## Project Structure

```
CREATE ACCOUNT
      |
Account Number + PIN
      |
    LOGIN
      |
+-------------------------+
|      ACCOUNT MENU       |
+-------------------------+
| 1. Check Balance        |
| 2. Deposit              |
| 3. Withdraw             |
| 4. Transfer             |
| 5. Transaction History  |
| 6. Change PIN           |
| 7. Logout               |
+-------------------------+
      |
    LOGOUT
      |
  MAIN MENU
```

## Input Validation

- The name must contain only letters and spaces.
- The phone number must be exactly 10 digits.
- The PIN must be exactly 4 digits.
- Amounts must be numbers greater than zero.
- Withdrawals and transfers are blocked when the balance is insufficient.
- Transfers to the same account or to a non-existent account are rejected.

## Sample Output

```
===== WELCOME TO PYTHON BANK =====
1. Create Account
2. Login
3. Exit
Enter your choice (1-3): 1

--- CREATE ACCOUNT ---
Enter your name: Kinjal
Enter phone number (10 digits): 9878765654
Create a 4-digit PIN: 3450
Confirm PIN: 3450

Account created successfully!
Account Holder : Kinjal
Account Number : 1807626055  (please remember this)
```

## Project Objective

The main objective of this project is to combine the Python concepts learned so far into one real-world application and to understand how individual concepts work together to build a functional system.

## Real-World Connection

This project demonstrates how programming concepts can be used to model a simplified version of real banking applications, such as account management, transactions, authentication and transaction records.

## Note

Account data is stored in memory using a Python dictionary, so all accounts are reset when the program is closed.

## Author

**Kinjal Nigam**
