# Banking-System

## Description
Banking system with desktop applications for ATMs and for bank tellers. Provides basic ATM functions and allows tellers to manage existing or new customers.

Built as a group project following the software development lifecycle (SDLC). Incorporates Object-Oriented Programming (OOP) principles and multithreaded client-server design pattern.

## Features
- GUI for ATM and a Bank Teller
- Login system for both
- ATM GUI provides all basic ATM functions for checkings/savings accounts
- Teller GUI allows management of customer accounts along with transfers to other accounts
- Updates files in realtime allowing for concurrent actions on same accounts
- Transaction history is saved onto file for each account

## Installation

### Prerequisites
- JUnit5 for testing
  - junit.jupiter
  - junit.platform.suite
- Java 20
1. Navigate to src folder
2. Compile Java files
```
javac app/*.java
```
3. Run Server.java.
```
java app.Server
```
4. Run GUI
  - Option 1: For ATM
  ```
  java app.ATMGUI
  ```
  - Option 2: For Bank Teller
  ```
  java app.BankTellerGUI
  ```

## Usage
ATM Usage:
After entering card number and corresponding PIN, customers can perform basic ATM functions.

![image](https://github.com/jlchuun/banking-system/assets/44554795/05441424-9c2a-4274-873f-c22cd6972cc1)

Bank Teller Usage:
After logging in with valid teller username and password, teller has options to manage customer accounts.

![image](https://github.com/jlchuun/banking-system/assets/44554795/ba92d58b-4f50-4e31-92f5-c5ed412f6c12)




## Credits
Joshua Chung
- https://github.com/joshualchung
- https://github.com/jlchuun

Brandon Chau
- https://github.com/BurandonC


 
