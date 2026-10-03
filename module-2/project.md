# Project - Simple ATM Simulator

The exercises in this module have progressively introduced the capabilities required for this project.

You will now combine them into a single program.

## Problem

Build a command-line ATM simulator.

The program should begin with an account balance and require the user to enter a PIN.

Use:

```text
PIN: 1234
Starting balance: 100000
```

If the PIN is incorrect, the program should display an appropriate error message.

If the PIN is correct, display a menu:

```text
1. Check balance
2. Deposit money
3. Withdraw money
4. Exit
```

The user should be able to select an option.

### Check Balance

Display the current account balance.

### Deposit Money

Ask the user how much they want to deposit and add that amount to the balance.

### Withdraw Money

Ask the user how much they want to withdraw.

If the user has enough money, subtract the amount from the balance.

If they do not have enough money, display:

```text
Insufficient funds.
```

### Exit

Display an appropriate message and end the program.

The menu should continue to appear after each operation until the user chooses to exit.

## Example

```text
Enter PIN: 1234

Login successful.

1. Check balance
2. Deposit money
3. Withdraw money
4. Exit

Choose an option: 1

Balance: 100000

1. Check balance
2. Deposit money
3. Withdraw money
4. Exit

Choose an option: 3

Amount to withdraw: 25000

Withdrawal successful.
Balance: 75000

1. Check balance
2. Deposit money
3. Withdraw money
4. Exit

Choose an option: 4

Thank you for using the ATM.
```

## Before You Code

Do not begin by writing Python.

First identify:

### Inputs

What information does the program receive?

### Processing

What decisions and calculations need to happen?

### Outputs

What information should the program display?

### Conditions

What decisions does the program need to make?

For example:

* Is the PIN correct?
* Is the selected menu option valid?
* Is there enough money to withdraw?
* Should the menu appear again?

### Repetition

What actions need to happen repeatedly?

### Algorithm

Write the steps of the solution in plain English or pseudocode.

You may also draw the program's flow before writing the code.

## Requirements

Your program must use:

* Variables
* User input
* Type conversion
* Boolean expressions
* `if`
* `elif`
* `else`
* `while`
* Arithmetic
* Comparison operators
* Logical reasoning

The program should:

* Check the user's PIN.
* Display a menu after successful login.
* Allow the user to check their balance.
* Allow deposits.
* Allow withdrawals.
* Prevent withdrawals when there are insufficient funds.
* Continue showing the menu until the user chooses to exit.
* Display clear messages to the user.

## Testing

Test your program with different situations.

At minimum, test:

1. Correct PIN.
2. Incorrect PIN.
3. Checking the balance.
4. Depositing money.
5. Withdrawing money.
6. Attempting to withdraw more than the available balance.
7. Performing multiple operations.
8. Choosing the exit option.

## Bonus

Add a withdrawal limit.

For example:

```text
Maximum withdrawal: 50000
```

The program should reject a withdrawal above this limit.

Also prevent the user from entering negative amounts for deposits or withdrawals.
