# 🏦 Bank System in Java (Fixed Number of Accounts)

## 📌 Overview
This project simulates a simple **Bank System** in Java with a fixed number of accounts.  
The system allows deposits, withdrawals, and transfers while enforcing constraints like maximum accounts and preventing overdraft.  
It demonstrates **OOP concepts** such as **Encapsulation, Abstraction, and Constructor Overloading**.

## 🛠 Features
- Maximum **10 accounts** (fixed array-based implementation).
- Each account stores:
  - Owner name
  - Balance
  - Unique account number (auto-generated)
- Supported operations:
  - **Deposit** money
  - **Withdraw** money (prevents overdraft)
  - **Transfer** money between accounts
- No **ArrayList** or other collections — uses only **arrays**.
- Demonstrates **constructor overloading** for creating accounts with/without initial balance.

## 🏗 Design
- **Account (Class)**  
  - Fields: `ownerName`, `balance`, `accountNumber`  
  - Methods: `deposit()`, `withdraw()`, `transfer()`, `getDetails()`  
  - Constructor Overloading: 
    - Create account with just owner name
    - Create account with owner name + initial balance
- **Bank (Class)**  
  - Manages an array of max 10 accounts.  
  - Handles account creation, searching by account number, and transactions.  
- **Main (Simulation Class)**  
  - Runs the program, creates accounts, and performs transactions.

## 📚 OOP Concepts Used
- **Encapsulation** → Private fields for account details with public getters/setters.
- **Abstraction** → Bank hides internal implementation of account storage.
- **Constructor Overloading** → Account creation with or without initial balance.
