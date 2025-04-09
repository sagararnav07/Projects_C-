# Bank Data Management System

A simple C++ console-based application that simulates basic banking operations like creating an account, depositing and withdrawing money, and checking account information. The system uses text files to store and manage account data.

## Features

- **Create Account**: Generates a unique account number and stores user details including name, father's name, CNIC, phone number, email, and initial deposit.
- **Deposit Amount**: Allows depositing money into an existing account.
- **Withdraw Amount**: Allows withdrawing money from an existing account.
- **Check Account Info**: Displays all saved information related to a given account.

## Technologies Used

- **Language**: C++
- **File Handling**: Uses `fstream` for reading from and writing to text files.

## File Structure

- `project1.cpp` — Main source file containing all logic.
- `data.txt` — Stores all account records.
- `data1.txt` — Temporary file used during deposit/withdraw operations for updating records.

## How to Run

1. Compile the code:
   ```bash
   g++ project1.cpp -o bankSystem
# Projects_C-
