🏦 Banking Application
A simple console-based banking application written in Java that allows users to manage their bank accounts.
This project demonstrates Object-Oriented Programming (OOP) concepts such as encapsulation, nested classes, arrays, and string handling.

🚀 Features
➕ Create new bank accounts
💰 Deposit money into an account
💸 Withdraw money with balance validation
👤 View account details (account number, holder name, balance, contact info)
✏️ Update email & phone number
📋 Menu-driven interface
Supports up to 100 accounts
🏗️ Project Structure
The application is written in a single file: BankingApplication.java

Account (nested static class)

Stores account information: account number, name, balance, email, phone
Provides methods: deposit(), withdraw(), displayAccountDetails(), updateContactDetails()
UserInterface (nested static class)

Handles user interaction via menu-driven options
Manages multiple accounts in an array
Provides methods: createAccount(), performDeposit(), performWithdrawal(), showAccountDetails(), updateContact()
BankingApplication (main class)

Entry point of the program (main() method)
Creates UserInterface object and starts the application
⚙️ Technologies Used
Java (Core Java)
Object-Oriented Programming (Encapsulation, Classes, Objects)
Control Structures (if-else, switch, loops)
Arrays & Strings
Scanner Class (for console input)
