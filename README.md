ATM Machine Simulation in Python

This repository contains a console-based ATM (Automated Teller Machine) simulation developed in Python. The project emulates basic banking operations, providing users with an interactive experience to manage their virtual bank account.

Features

User Authentication:

Secure access with PIN verification to ensure authorized usage.


Banking Operations:

Balance Inquiry: Check the current account balance.

Cash Withdrawal: Withdraw funds with checks for sufficient balance.

Cash Deposit: Deposit funds, updating the account balance accordingly.

PIN Change: Update the account PIN after verifying the current one.

Transaction History: View a log of all transactions performed during the session.


User-Friendly Interface:

Menu-driven navigation with clear prompts.

Input validation and error handling to guide users through each operation seamlessly.



Code Overview

The application is structured to simulate a real-world ATM experience:

1. Startup Sequence:

Displays a welcome message and simulates card insertion with a brief delay.



2. Authentication:

Prompts the user to enter a PIN.

Verifies the entered PIN against a predefined password to grant access.



3. Main Menu:

Presents a list of available banking operations.

Continuously displays the menu after each operation until the user chooses to exit.



4. Operations:

Balance Inquiry: Displays the current balance.

Cash Withdrawal: Prompts for the withdrawal amount, checks for sufficient funds, and updates the balance.

Cash Deposit: Prompts for the deposit amount and updates the balance.

PIN Change: Allows the user to set a new PIN after verifying the current one.

Transaction History: Maintains and displays a list of all transactions during the session.



5. Exit Sequence:

Upon exiting, the application displays the transaction history and a thank-you message.




