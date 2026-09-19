# Task 4 – Bank Account Management System

## Project Overview

This project is a simple **Bank Account Management System** created using Python and Object-Oriented Programming (OOP).

The purpose of this project is to understand how classes and objects can be used to create a simple real-world application. The program allows users to create bank accounts and perform basic banking operations such as depositing, withdrawing, checking balance, and viewing account information.

## Objective

The main objective of this project is to practice:

- Classes and Objects
- `__init__` method
- `self`
- Methods
- Basic Encapsulation
- Conditional Statements
- Loops
- Lists
- Searching objects

## Features

The system provides the following options:

1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Display Account Information
6. Exit

## Account Information

Each account contains:

- Account Holder Name
- Account Number
- Balance

## How the Program Works

When the program starts, it displays a menu with different options.

The user can create an account by entering the account holder's name, account number, and initial balance.

After creating an account, the user can use the account number to:

- Deposit money
- Withdraw money
- Check the current balance
- View account information

The program also checks whether the account exists before performing banking operations.

## OOP Implementation

A class named `BankAccount` is used to represent each bank account.

The class contains:

```python
class BankAccount:
```

The `__init__` method is used to initialize the account details:

```python
def __init__(self, name, account_number, balance=0):
```

Different methods are used for different operations, such as:

- `deposit()`
- `withdraw()`
- `check_balance()`
- `display_information()`

Multiple account objects are stored inside a list so that accounts can be searched using their account numbers.

## Example

```text
Bank Account System 
1. Create Account
2. Deposit
3. Withdraw
4. Check Balance
5. Account Information
6. Exit

Enter your choice: 1
Enter Account Holder Name: Asifa
Enter Account Number: 1001
Enter Initial Balance: 5000

Account created successfully.
```

## Technologies Used

- Python
- Object-Oriented Programming (OOP)

## Project File

```text
bank_account.py
```

## How to Run

1. Install Python on your computer.
2. Open the project folder in VS Code.
3. Open the `bank_account.py` file.
4. Run the program using:

```bash
python bank_account.py
```

## Learning Outcome

Through this project, I learned how to create classes and objects in Python and how to use methods to perform different operations. I also practiced storing multiple objects in a list and searching for an account using its account number.

## Future Improvements

The project can be improved by adding:

- Transaction history
- File handling
- PIN/Login system
- Different account types
- Saving account data permanently

## Author

**Asifa Asghar**
