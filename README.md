Project Description
This ATM (Automated Teller Machine) console application is developed using C# with a strong emphasis on object-oriented programming principles and robust exception handling. The application simulates the core functionalities of a real ATM machine while demonstrating proper software engineering practices.

Key Features
1. Object-Oriented Design
Implemented using classes and objects to represent real-world entities

Proper encapsulation of data members with private access modifiers

Inheritance used for different account types (Savings, Current)

Polymorphism demonstrated through method overriding

Abstraction achieved through abstract classes and interfaces

2. Exception Handling
Comprehensive exception handling throughout the application

Custom exceptions for specific ATM scenarios (InsufficientFundsException, InvalidAmountException)

Try-catch-finally blocks for graceful error recovery

Input validation to prevent invalid user entries

3. Core Functionalities
User authentication with PIN verification

Account balance inquiry

Cash withdrawal with denomination breakdown

Cash deposit

Fund transfers between accounts

Mini-statement generation

PIN change functionality

4. Additional Features
Transaction history tracking

Session management

Secure password handling

Clean console interface with proper formatting

Data persistence (simulated with in-memory storage or file system)

Technical Implementation
The application is structured with these main components:

ATM Class: Main controller that orchestrates the application flow

Account Classes: Base Account class with derived SavingsAccount and CurrentAccount classes

Transaction Classes: Handles different transaction types with proper validation

User Interface: Console-based menu system with clear prompts

Exception Classes: Custom exceptions for domain-specific error cases

Learning Outcomes
Through this project, we've demonstrated:

Proper application of OOP principles in a real-world scenario

Effective exception handling strategies

Clean code practices with proper modularization

User input validation techniques

State management in a console application

The application serves as a comprehensive example of how to build a robust, maintainable console application in C# while following software engineering best practices.
