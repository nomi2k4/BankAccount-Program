BankAccount Program

Description

This C++ program simulates a simple bank account, allowing users to check their balance, deposit, and withdraw money.

Features

* Allows the user to check their account balance.
* Allows the user to deposit money into their account.
* Allows the user to withdraw money from their account.
* Provides basic input validation for deposits and withdrawals.

Code Structure

The code consists of the following files:

* main.cpp: Contains the main function, which provides the user interface and interacts with the BankAccount class.
* header.h: Contains the declaration of the BankAccount class.
* BankAccount.cpp: Contains the implementation of the BankAccount class methods.

The BankAccount class encapsulates the data and functions to manage a bank account. It includes functions for getting the balance, setting the balance, depositing, and withdrawing money.

Dependencies

* iostream: For input/output operations.

Compilation and Execution

To compile and run the program:

1.  Save the files as main.cpp, header.h, and BankAccount.cpp.
2.  Use a C++ compiler (e.g., g++) to compile the code:

    g++ main.cpp BankAccount.cpp -o bank_account

3.  Run the executable:

    ./bank_account