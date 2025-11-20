# ANSH--25bai10886-ATM_machine-


Simple ATM Machine (Python)

Hi my name is ansh sonkar I made this project under vityarthi project This project is a small ATM program made in Python.
The goal was just to understand how to use functions, loops and dictionaries.
The user can create an account, log in with a PIN, and then use basic ATM options.

What the program can do

Make a new account

Log in using account number + PIN

Deposit money

Withdraw money

Check balance

Logout and go back to main menu


How it works

All the account details are stored in a dictionary called accounts.
Each account saves two things:

the PIN

the current balance


Everything runs through simple menus.
After logging in, the user gets the ATM menu where they can choose what to do.

Files / Functions

create_account() → makes a new account

login() → checks account number and PIN

deposit() → adds money

withdraw() → removes money if balance is enough

check_balance() → shows balance

atm_menu() → menu after