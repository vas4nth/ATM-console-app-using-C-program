ATM Console Application in C#

Project Description
This ATM (Automated Teller Machine) console application is developed using C# with a strong emphasis on object-oriented programming principles and robust exception handling. The application simulates the core functionalities of a real ATM machine while demonstrating proper software engineering practices.

Key Features
1. Object-Oriented Design
   
    i.Implemented using classes and objects to represent real-world entities
    
    ii.Proper encapsulation of data members with private access modifiers
    
    iii.Inheritance used for different account types (Savings, Current)
    
    iv.Polymorphism demonstrated through method overriding
    
    v.Abstraction achieved through abstract classes and interfaces

2. Exception Handling
   
    i.Comprehensive exception handling throughout the application
    
    ii.Custom exceptions for specific ATM scenarios (InsufficientFundsException, InvalidAmountException)
    
    iii.Try-catch-finally blocks for graceful error recovery
    
    iv.Input validation to prevent invalid user entries

3. Core Functionalities
   
    i.User authentication with PIN verification
    
    ii.Account balance inquiry
    
    iii.Cash withdrawal with denomination breakdown
    
    iv.Cash deposit
    
    v.Fund transfers between accounts
    
    vi.Mini-statement generation
    
    vii.PIN change functionality

4. Additional Features
   
    i.Transaction history tracking
    
    ii.Session management
    
    iii.Secure password handling
    
    iv.Clean console interface with proper formatting
    
    v.Data persistence (simulated with in-memory storage or file system)

   5.Technical Implementation
   
      The application is structured with these main components:
      
        i.ATM Class: Main controller that orchestrates the application flow
        
        ii.Account Classes: Base Account class with derived SavingsAccount and CurrentAccount classes
        
        iii.Transaction Classes: Handles different transaction types with proper validation
        
        iv.User Interface: Console-based menu system with clear prompts
        
        v.Exception Classes: Custom exceptions for domain-specific error cases

   6.Learning Outcomes
   
      Through this project, we've demonstrated:
      
        i.Proper application of OOP principles in a real-world scenario
        
        ii.Effective exception handling strategies
        
        iii.Clean code practices with proper modularization
        
        iv.User input validation techniques
        
        v.State management in a console application

The application serves as a comprehensive example of how to build a robust, maintainable console application in C# while following software engineering best practices.
