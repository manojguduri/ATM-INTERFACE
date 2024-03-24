# ATM INTERFACE

This project simulates basic ATM operations using Java classes for a bank account and ATM functionalities.

## Project Structure

The project consists of the following classes:
- `BankAccount`: Manages bank account operations such as deposit, withdrawal, and balance checking.
- `ATM`: Simulates ATM operations like withdrawing, depositing, checking balance, and displaying a menu.

## Requirements

To run the program, you need:
- Java Development Kit (JDK) installed on your machine.
- A Java IDE or command-line tools to compile and run Java programs.

## How to Run

1. Clone or download the project files to your local machine.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the Java files (`ATM_Main.java`, `BankAccount.java`, `ATM.java`).
4. Compile the Java files using the `javac` command:
```
javac ATM_Main.java
```
5. Run the compiled program using the `java` command:
```
java ATM_Main
```


## Usage

- Upon running the program, you will see an ATM menu with options to withdraw, deposit, check balance, and exit.
- Enter your choice by typing the corresponding number and following the prompts.
- Follow the on-screen instructions to perform ATM operations with the simulated bank account.

## Notes

- The initial balance for the bank account is set to $1000 in the provided code. Modify it as needed.
- Ensure valid input (numeric values) when depositing or withdrawing amounts.
- The program loops until you choose to exit (`4` in the menu).
