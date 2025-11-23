Title : Modular Python Login Checker

Overview of the Project:

    This is a Python application designed to simulate a user authentication system. 
    The main aim of this project is to demonstrate modular programming by clearly separating the application into three distinct layers: Data, Logic, and Presentation. 
    This structure ensures the code is clean and manageable

Features:

Modular Design:  Code is separated into three separate  files/modules based on function.

Credential Verification:  Checks user input against a list of valid, predefined username and password pairs.

Login Loop:   Allows a user a maximum of 3 attempts to log in before locking them out.

Password Security Checks : Includes logic to enforce minimum password length, and the presence of uppercase, lowercase, digits, and special characters.


Technologies/Tools Used:

Primary Language: Python 3.x

Code Editor: Any text editor or IDE.

Execution Environment: Command Line Interface .

Libraries: The built-in Python module re (Regular Expressions) is used for password security checks.


Steps to Install & Run the Projec
The project requires no special installation beyond having Python installed.

1.Project Setup
Create a new directory for the project:
        mkdir modular_login_checker
        cd modular_login_checker        (in terminal)
Ensure the three source files (credentials.py, validation.py, and main_app.py) are saved directly inside this new directory.

2.Run the Application
Execute the main file (main_app.py) from your terminal:
     python main_app.py    (in terminal)

Instructions for Testing:
The system will prompt you for a username and password upon execution. Use the following scenarios to test the system's logic and error handling:

 Valid Credentials
 
Username--> admin    
Password --> Secure!123    
Expected Result -->  Success:Login Successful! Welcome back.


inValid Credentials 

Scenario     
Input Username --> admin   
Input Password --> 12345    
Expected Result --> Failure:Login Failed: Invalid password   

Screenshots
         ![alt text](<Screenshot 2025-11-22 200535.png>)
         ![alt text](<Screenshot 2025-11-22 200651.png>)
