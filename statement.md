Project Statement: Modular Python Login Checker

1.Problem Statement
     The goal is to design a user authentication system that is robust, easy to maintain, and scalable, specifically addressing the challenge of mixing application logic with data storage and user interaction. 
     In small, monolithic projects, credential checking, security rules, and user interface prompts often reside in the same file, leading to "spaghetti code."
      The problem is to demonstrate a cleaner, professional coding practice where these concerns are isolated, allowing developers to change security rules without touching the user interface, or change stored data without affecting the login algorithm.



2.Scope of the Project
The scope of this project is strictly focused on backend credential validation within a command-line interface (CLI).

In Scope:

  Separation of code into three distinct modules: Data (credentials.py), Logic (validation.py), and Presentation (main_app.py).
  Basic username/password verification against hardcoded values.
  Implementation of security rules for password complexity (length, character requirements).
  Login attempt limits (3 tries).



Out of Scope (Future Work):

Persistent storage (e.g., saving data to a file or database).
Password hashing (storing passwords securely).
Web/Graphical User Interface (GUI).
Account creation/deletion functionality.



3.Target Users
The primary target users for this project are:

  Beginner/Intermediate Python Developers: Individuals learning about modularity, the import statement, and professional project structure.
  Instructors/Trainers: People looking for a simple, clear code example to teach the concept of Separation of Concerns.
  Project Developers: Engineers needing a quick, simple, yet structurally sound template for basic authentication logic in a non-production environment.


  4.High-Level Features  
  
  Feature Category     
                Authentication Core    
                User Experience    
                Code Structure   
                    
  High-Level Feature     
                 Modular Credential Checking    
                 Login Attempt Limitation  
                 Clear Functional Abstraction   

  Description    
               The core login logic resides in one file (validation.py) and successfully verifies input against data sourced from another file (credentials.py)    
               The system enforces a maximum of 3 login attempts before terminating access for security.Includes checks for minimum length (8 chars) and required complexity (uppercase,digit,special character) during registration checks.         
              The project utilizes 8 distinct functions, each responsible for one clear task
                                                        
 



                                                         
