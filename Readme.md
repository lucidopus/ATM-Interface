# ATM Banking System

This is a simple Java-based ATM Banking System that provides core banking functionalities such as creating accounts, viewing balances, depositing funds, and withdrawing funds. The project is designed with modular code, object-oriented practices, and uses a simple command-line interface.

## Overview

This project simulates an ATM banking system, handling both Current and Savings account transactions. The system is organized using separate classes to maintain clear, modular code and is designed for ease of testing and expansion.

### Main Components

1. **Account Management** - Handles all functionalities for account transactions.
2. **Login System** - Simple login with account number and PIN validation.
3. **User Interface** - Console-based interaction allowing users to choose account type and perform transactions.

## Features

- **Login System**: Allows a user to log in using a customer ID and PIN.
- **Account Types**: Supports both Current and Savings accounts.
- **Balance Inquiry**: Users can view the balance in their accounts.
- **Deposit Funds**: Users can deposit money into their accounts.
- **Withdraw Funds**: Users can withdraw money from their accounts with balance validation.
- **Error Handling**: Basic error handling for invalid entries and insufficient funds.

## Structure

The project has three main classes:

- **Account.java**: Core class for handling account information and transactions.
- **OptionMenu.java**: Handles user interaction, login validation, and account selection.
- **Main.java**: The entry point, initializing the OptionMenu and launching the login process.

## Setup

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- Basic familiarity with running Java programs from the command line.

### Running the Project

1. Clone the repository or download the files.
2. Compile the classes:
   ```bash
   javac ATM/Account.java ATM/OptionMenu.java ATM/Main.java
   ```

### Running the main class
    ```bash
    java ATM.Main
    ```

## Usage Instructions

Once the program is running, follow these steps to interact with the ATM Banking System.

### 1. Login

1. When prompted, enter your **Customer ID** and **PIN** to log in.
2. For testing, use the following sample credentials:
   - **Customer ID**: `1234`
   - **PIN**: `5678`

### 2. Main Menu

After a successful login, you’ll be presented with options to access your accounts.

1. **Select Account Type**:
   - Type `1` for **Current Account**
   - Type `2` for **Savings Account**
   - Type `3` to **Exit** the session

2. **Choose Account Options**:
   - **View Balance**: Check the current balance in the selected account.
   - **Withdraw Funds**: Withdraw a specified amount from your account. The system checks for sufficient balance before proceeding.
   - **Deposit Funds**: Deposit a specified amount into your account.
   - **Exit**: Return to the account type selection menu.

### 3. Example Workflow

Here’s a sample flow of how you might interact with the ATM system:

1. **Log In** using Customer ID and PIN.
2. Select **Current Account** or **Savings Account**.
3. Choose one of the following:
   - **View Balance** to check your account balance.
   - **Withdraw Funds** to withdraw a specific amount.
   - **Deposit Funds** to add funds to your account.
4. After completing your transactions, select **Exit** to log out.

**Note**: All amounts entered for withdrawals and deposits should be non-negative. If an invalid entry is made, the system will prompt you with an error message.

---

This completes the usage instructions. Enjoy using the ATM Banking System!