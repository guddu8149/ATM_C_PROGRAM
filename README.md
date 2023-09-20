# ATM_C_PROGRAM

The program starts by declaring and initializing some variables:

amount: Represents the current balance in the ATM.
deposit: Stores the amount to be deposited.
withdraw: Stores the amount to be withdrawn.
choice: Represents the user's choice from the menu.
pin: Stores the user's PIN.
k: A flag variable used to control the program loop.
transaction: Stores the user's choice to continue with another transaction.
The while loop is used to validate the user's PIN. It continues to prompt the user until a valid PIN (0000) is entered.

After the PIN is validated, a do-while loop is used to display the ATM menu and perform transactions until the user decides to quit.

Inside the loop, the user is presented with the following options:

Check Balance
Withdraw Cash
Deposit Cash
Quit
The user is prompted to enter their choice.

Depending on the choice, the program executes the corresponding case in the switch statement:

Case 1: Displays the account balance.
Case 2: Allows the user to withdraw cash, with checks for multiples of 100 and sufficient balance.
Case 3: Allows the user to deposit cash.
Case 4: Exits the program.
After each transaction, the user is asked if they want to perform another transaction (transaction variable).

The loop continues until the user decides to quit (k flag set to 1), at which point a thank you message is displayed.

Note:

The PIN validation in this code is very simple (a fixed PIN of 0000). In a real-world application, you would want a more secure and dynamic way of validating user credentials.
The code uses unsigned long integers for balance, deposit, and withdrawal amounts. Depending on your requirements, you may want to use a different data type, such as double, to handle decimal values.
Overall, this is a basic ATM simulation program that demonstrates the flow of an ATM transaction system. However, for practical use, it would need significant enhancements in terms of security, data storage, and error handling.




