# Java Bank Account System

A Java console application developed for a Programming II coursework assignment. The project demonstrates fundamental object-oriented programming concepts through a simple bank account and checking account implementation.

## Project Overview

The application creates a checking account, assigns account holder information, processes a deposit and withdrawal, and displays an account summary.

The project focuses on class inheritance, methods, object state, and basic financial operations.

## Features

- Create a checking account using object-oriented design
- Store account holder information, account ID, and balance
- Deposit funds into an account
- Process withdrawals and update the account balance
- Apply a $30 overdraft fee when a withdrawal results in a negative balance
- Store an interest rate for the checking account
- Display account information and the current balance

## Object-Oriented Programming Concepts

### Inheritance

The `CheckingAccount` class extends the `BankAccount` class, inheriting its account information and methods.

### Classes and Objects

The application uses three Java classes:

- `BankAccount.java` — Defines account information, deposit and withdrawal methods, getters, setters, and an account summary.
- `CheckingAccount.java` — Extends `BankAccount` with overdraft processing and an expanded account display.
- `Main.java` — Creates a checking account and demonstrates the application's functionality.

### Methods and State Management

The program uses methods to modify and retrieve account information, demonstrating how an object's state changes during financial transactions.

## Project Structure

```text
java-bank-account-system/
├── src/
│   ├── BankAccount.java
│   ├── CheckingAccount.java
│   └── Main.java
├── .gitignore
├── LICENSE
└── README.md
```

## How to Run

### Requirements

- Java Development Kit (JDK)
- Terminal or command prompt

### Instructions

1. Clone or download the repository.
2. Open a terminal in the repository's root directory.
3. Compile the Java source files:

   ```bash
   javac src/BankAccount.java src/CheckingAccount.java src/Main.java
   ```

4. Run the application:

   ```bash
   java -cp src Main
   ```

The program demonstrates the following sequence:

1. Creates a checking account.
2. Assigns account holder information and an account ID.
3. Sets an interest rate.
4. Deposits $500.
5. Withdraws $200.
6. Displays the account summary.

The account begins with a balance of $0 and ends with a balance of $300.

## Educational Context

This project was developed as part of Programming II coursework at Colorado State University Global.

It represents an early implementation of Java inheritance and account management concepts. The original application structure is preserved to demonstrate programming progression throughout the degree program.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
