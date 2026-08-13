============================================================
              BANK MANAGEMENT APPLICATION
============================================================

PROJECT TITLE
-------------
Bank Management Application


PROGRAMMING LANGUAGE
--------------------
C++


PROJECT DESCRIPTION
-------------------
The Bank Management Application is a console-based C++
application designed to simulate basic banking operations.

The project uses Object-Oriented Programming (OOP) concepts
and file handling to maintain customer account information.

The system allows users to create accounts, deposit money,
withdraw money, check account balances, and display all
stored customer accounts.


OBJECTIVES
----------
1. To develop a basic banking application using C++.
2. To understand and implement Object-Oriented Programming.
3. To use classes and objects in a real-world application.
4. To implement deposit and withdrawal operations.
5. To implement balance enquiry functionality.
6. To store customer records using file handling.
7. To maintain customer information permanently in a file.


KEY FEATURES
------------
1. Create Account
   - Creates a new customer bank account.
   - Stores account number, customer name, and initial balance.

2. Deposit Money
   - Allows the user to deposit money into an existing account.
   - Updates the account balance.

3. Withdraw Money
   - Allows the user to withdraw money.
   - Prevents withdrawal when the requested amount is greater
     than the available balance.

4. Check Balance
   - Displays the current balance of a particular account.

5. Display All Accounts
   - Displays all customer accounts stored in the system.

6. File Handling
   - Customer information is stored in accounts.txt.
   - Account information remains available after closing
     and restarting the program.


OOP CONCEPTS USED
-----------------
1. Class
   The BankAccount class represents a bank account.

2. Object
   Objects of the BankAccount class represent individual
   customer accounts.

3. Encapsulation
   Account number, customer name, and balance are declared
   as private data members.

4. Constructors
   Default and parameterized constructors are used to
   initialize account objects.

5. Member Functions
   Functions such as deposit(), withdraw(), and display()
   operate on account data.


FILE HANDLING
-------------
The project uses C++ file handling classes:

ifstream
    Used for reading account information from accounts.txt.

ofstream
    Used for writing account information to accounts.txt.

The file stores data in the following format:

AccountNumber|CustomerName|Balance

Example:

1001|Rahul Kumar|5000.00
1002|Anjali Sharma|7500.00


PROJECT FILES
-------------
bank_management.cpp
    Main C++ source code.

accounts.txt
    Stores customer account information.

README.txt
    Contains project description and instructions.


REQUIREMENTS
------------
1. C++ compiler
2. Windows, Linux, or macOS
3. Any C++ IDE such as:
   - Code::Blocks
   - Visual Studio Code
   - Visual Studio
   - Dev-C++
   - Online C++ compiler


HOW TO COMPILE
--------------
If you are using g++:

g++ bank_management.cpp -o bank_management


HOW TO RUN
----------
Windows:

bank_management.exe


Linux/macOS:

./bank_management


HOW TO USE THE PROGRAM
----------------------

Step 1:
Run the program.

Step 2:
Select option 1 to create a new account.

Example:

Enter account number: 1001
Enter customer name: Rahul Kumar
Enter initial deposit: 5000


Step 3:
Select option 2 to deposit money.

Example:

Enter account number: 1001
Enter amount to deposit: 2000

New balance:

7000.00


Step 4:
Select option 3 to withdraw money.

Example:

Enter account number: 1001
Enter amount to withdraw: 1000

New balance:

6000.00


Step 5:
Select option 4 to check the balance.

Step 6:
Select option 5 to display all accounts.

Step 7:
Select option 6 to exit the application.


SAMPLE MENU
-----------

========================================
       BANK MANAGEMENT SYSTEM
========================================
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Display All Accounts
6. Exit
========================================
Enter your choice:


SAMPLE ACCOUNT
---------------

Account Number : 1001
Customer Name  : Rahul Kumar
Balance        : Rs. 5000.00


EXPECTED OUTCOME
----------------
The application provides a functional banking system capable
of performing:

- Account creation
- Deposits
- Withdrawals
- Balance enquiries
- Customer record storage
- Customer record retrieval

The application demonstrates the use of C++ Object-Oriented
Programming and file management.


CONCLUSION
----------
The Bank Management Application successfully demonstrates how
C++ can be used to create a simple banking system.

The project combines classes, objects, constructors,
encapsulation, functions, conditional statements, loops, and
file handling to maintain persistent customer records.

This project provides a basic understanding of how
object-oriented programming and file management can be applied
to a real-world banking application.


IMPORTANT NOTE
--------------
This project is an academic demonstration. A real banking
system would require authentication, encryption, secure
databases, transaction logging, access control, and many
additional security mechanisms.
