# ATM Simulation Project

This Java project simulates a simple ATM system with basic banking operations. Users can log in, view balance, withdraw money, deposit money, transfer funds, and check transaction history.

## Project Structure

The project is organized into the following classes:

- `Transaction`: Represents a financial transaction with an amount and timestamp.
- `Account`: Defines a bank account with an account number, PIN, balance, and transaction history.
- `User`: Represents a user with a unique ID, PIN, and associated bank account.
- `ATM`: The main class orchestrating the ATM functionalities, user interactions, and menu options.

## Usage

1. Compile the project using a Java compiler or an integrated development environment (IDE).

2. Run the `ATM` class to start the ATM simulation.

3. Follow on-screen prompts to log in and perform banking operations.

## Example User Accounts

The program comes with pre-defined user accounts for testing:

1. User ID: 101, PIN: 1234, Balance: Rs 10,000.0
2. User ID: 102, PIN: 1112, Balance: Rs 20,000.0
3. User ID: 103, PIN: 9220, Balance: Rs 50,000.0
4. User ID: 104, PIN: 2341, Balance: Rs 40,000.0
5. User ID: 105, PIN: 4567, Balance: Rs 150,000.0

## Dependencies

The project does not have external dependencies. It is designed to run on Java SE 8 or later.
