# Door-Verification-Code
A modular C program for a door code verification system with features like code entry, incorrect attempt handling, password reset with a security question, and a maximum retry limit, using if-else statements and functions.

Features-
Password Verification: Users can enter a predefined door code to unlock the door.
Incorrect Code Handling: The program provides feedback if the entered code is incorrect.
Password Reset Option:
If the code is incorrect, users can choose to reset the password.
Password reset is secured by a simple security question.
Feedback Messages: Displays appropriate messages based on user actions (success, incorrect attempts, or denied access).

Key Concepts-
Functions:
promptForCode(): Handles the initial code entry and verification.
handleIncorrectCode(): Manages incorrect code scenarios.
askToResetPassword(): Allows users to decide if they want to reset the password.
verifySecurityQuestion(): Verifies the answer to the security question before resetting.
Conditional Statements: Used extensively to handle different user inputs and responses.
Input/Output: scanf for user input and printf for displaying messages.

Use Cases-
This program is ideal for:
Demonstrating how a simple door lock system works.
Learning the basics of input validation, conditional logic, and modular programming in C.
Experimenting with password reset and security question mechanisms.

Feel free to fork this repository and extend its functionality with features like dynamic password updates, multiple users, or additional security layers!
