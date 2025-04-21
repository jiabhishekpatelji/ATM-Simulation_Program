# ATM-Simulation_Program
💳 ATM Simulation Program in C
  This is a simple C program that simulates the basic functionalities of an ATM (Automated Teller Machine), including checking balance, withdrawing money, depositing money, 
  and exiting the system.


*🧾 Features
✅ Check account balance
💸 Withdraw money
💰 Deposit money
🚪 Exit the ATM system



*📄 How It Works
The program uses a menu-driven approach with the following options:

--- ATM Menu ---
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. Exit
 





🧠 Program Structure
main()
Handles the main loop and menu display.

displayMenu()
Prints the ATM menu options.

checkBalance(float balance)
Displays the current account balance.

withdrawMoney(float *balance)
Allows the user to withdraw money if the balance is sufficient.

depositMoney(float *balance)
Allows the user to deposit money into the account.



*💻 Sample Output

--- ATM Menu ---
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. Exit


Please enter your choice: 1
Your current balance is: 100000.00 Rupees

--- ATM Menu ---
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. Exit
Please enter your choice: 2
Enter the amount to withdraw: Rupees5000
You have successfully withdrawn 5000.00 Rupees. Your new balance is: 95000.00 Rupees
🛠️ Requirements
C Compiler (e.g., GCC)

Basic knowledge of C programming

▶️ How to Run
Save the file as atm.c

Compile the code:
gcc atm.c -o atm

Run the executable:
./atm


📝 Notes
The initial balance is set to 100000.00 Rupees.
Error handling is included for invalid choices and transaction limits (e.g., negative amounts, insufficient balance).
 
