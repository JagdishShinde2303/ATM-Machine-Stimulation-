🚀 ATM Machine Simulation in Python

📌 Introduction

This project is a console-based ATM machine simulation built using Python. It provides a menu-driven interface that allows users to securely access their accounts and perform essential banking operations like balance inquiry, cash withdrawal, deposit, PIN change, and transaction history tracking.

✨ Features

✅ User Authentication – Secure PIN-based login system.
✅ Balance Inquiry – Displays the current account balance.
✅ Cash Withdrawal – Withdraw money while checking for sufficient balance.
✅ Cash Deposit – Deposit funds and update the account balance.
✅ Change PIN – Allows the user to update the PIN after verification.
✅ Transaction History – Stores and displays all transactions during the session.
✅ Error Handling – Prevents invalid inputs using try-except statements.
✅ Looping Menu – Enables continuous operation until the user exits.

🛠️ Installation & Usage

🔹 Prerequisites

Python 3.x installed on your system.


🔹 Clone the Repository

git clone https://github.com/yourusername/ATM-Machine-Simulation.git
cd ATM-Machine-Simulation

🔹 Run the Application

python atm_simulation.py

🔹 How to Use

1️⃣ Enter your PIN to log in (default: 8262).
2️⃣ Choose an option from the menu:

🏦 Check balance

💸 Withdraw cash

💰 Deposit money

🔑 Change PIN

📜 View transaction history
3️⃣ Follow on-screen instructions for each operation.
4️⃣ Select Exit to terminate the session.


📌 Example Output

Welcome to the ATM!
Please insert your card...

Please enter your PIN: ****

==================== ATM Menu ====================
1. Balance Inquiry
2. Cash Withdrawal
3. Cash Deposit
4. Change PIN
5. Transaction History
6. Exit
=================================================
Enter the option number you want to choose: 2

-- Cash Withdrawal --
Enter the amount you want to withdraw: 2000
Withdrawal successful! Your new balance is 8000 Rupees.

🚀 Future Enhancements

🔹 Database Integration – Store user data and transactions persistently.
🔹 Graphical User Interface (GUI) – Develop a GUI version for a better user experience.
🔹 Multi-User Support – Enable multiple accounts with unique PINs.
🔹 Security Improvements – Implement account lockouts after multiple failed attempts.

🤝 Contributing

Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.

📜 License

This project is open-source and available under the MIT License.

