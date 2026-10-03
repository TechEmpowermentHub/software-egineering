# Module 2- Control Flow and Program Logic

## What are we doing this week

In week 1, students learned how to write programs that receive information, process it, and produce an output.

This week, students will learn how programs make decisions and repeat actions.

They will use conditions to control what a program does and loops to perform actions repeatedly. They will also learn how to combine these ideas to solve problems that cannot be solved with a simple sequence of instructions.

The emphasis this week is on **program logic and problem solving**, not just learning Python syntax.

## Objectives

By the end of the week, students should be able to:

1. Explain what control flow is and why programs need it.
2. Use Boolean expressions to represent conditions.
3. Use if, elif, and else to make decisions.
4. Combine conditions using logical operators.
5. Use for and while loops to repeat instructions.
6. Understand the difference between condition-controlled and count-controlled repetition.
7. Identify and avoid common loop problems such as infinite loops.
8. Trace a program's execution step by step.
9. Break a problem involving decisions or repetition into computational steps.
9. Implement a small program using conditionals and loops.

## Concepts

1. Control Flow
    - What control flow means
    - Sequential execution
    - Decision-making
    - Repetition
    - How the flow of a program changes
2. Boolean Logic
    - Boolean values: True and False
    - Boolean expressions
    - Comparison operators
    - ==
    - !=
    - >
    - <
    - >=
    - <=
    - Logical operators
    - and
    - or
    - not
3. Conditional Statements
    - if
    - else
    - elif
    - Nested conditions
    - Multiple conditions
    - Choosing between alternative actions
4. Loops
    - Why repetition is useful
    - for loops
    - while loops
    - Loop conditions
    - Loop variables
    - range()
    - Updating variables inside loops
    - Infinite loops
    - Stopping a loop
5. Problem Solving with Control Flow
    - Identifying decisions in a problem
    - Identifying repeated actions
    - Writing conditions in plain English
    - Writing algorithms involving decisions
    - Writing algorithms involving repetition
    - Translating algorithms into Python
    - Tracing program execution

## Activities

1. Review of Week 1
    - Review variables and data types
    - Review expressions
    - Review input and output
    - Review the inputs → processing → outputs model
    - Review algorithms and pseudocode
    - Review the Personal Expense Calculator
2. Understanding Program Decisions
    - Understand how programs make decisions
    - Write simple Boolean expressions
    - Predict whether conditions are True or False
    - Use if, elif, and else
    - Build simple decision-making programs
3. Guided Programming Exercises
    - Boolean expressions
    - Comparisons
    - if statements
    - if/else
    - if/elif/else
    - Logical operators
    - Nested conditions
    - Simple for loops
    - range()
    - Simple while loops
    - Loop conditions
    - Counters and accumulators
4. Program Tracing

    Students will be given small programs and asked to determine what they will do before running them.

    They will practice:

    - Following variables through a program
    - Evaluating conditions
    - Tracking loop iterations
    - Predicting program output
    - Finding logical errors

5. Problem-Solving Exercise

    Students will take a real-world problem involving decisions or repetition and:

    - Identify the inputs
    - Identify the required decisions
    - Identify repeated actions
    - Identify the outputs
    - Describe the solution in plain English
    - Write pseudocode
    - Translate the solution into Python
    - Test the program with different inputs
6. Project Workshop
    - Understand the project requirements
    - Break the problem into smaller parts
    - Design the algorithm
    - Implement the program
    - Test different scenarios
    - Debug errors
    - Improve the program
    - Commit the project to Git
7. Code Review
    - Students demonstrate their programs
    - Compare different solutions
    - Trace important sections of code
    - Discuss readability and structure
    - Identify bugs
    - Discuss possible improvements
    - Explain why the program behaves the way it does

## Exercises

Do the exercises in the Exercises folder in order.

The exercises gradually introduce decisions, Boolean logic, and repetition. Students should complete them before beginning the module project.

## Project

**Simple ATM Simulator**

Build a command-line ATM simulator that allows a user to interact with a simple bank account.

The program should:

- Ask the user for a PIN
- Verify whether the PIN is correct
- Display an appropriate message when the PIN is incorrect
- Display an account menu when the PIN is correct
- Allow the user to check their balance
- Allow the user to deposit money
- Allow the user to withdraw money
- Prevent withdrawals when the user does not have enough money
- Allow the user to perform multiple operations
- Provide an option to exit the program

Students should first describe the algorithm and program flow before writing the Python code.

The project should require students to use:

- Variables
- User input
- Type conversion
- Boolean expressions
- Conditional statements
- Logical operators
- for or while loops
- Arithmetic
- Functions from previous or current exercises where appropriate
- Clear program output

The focus is not on building a real banking system. The focus is on using control flow to model a system with decisions and repeated actions.

```text
    START
    ↓
    Enter PIN
    ↓
    Correct?
    ┌───────┴───────┐
    NO              YES
    ↓                ↓
    Reject          Menu
                    ↓
                Choose action
                    ↓
            ┌───────┼────────┐
            Balance Deposit Withdraw
            │        │         │
            └────────┼─────────┘
                    ↓
                Return to menu
                    ↓
                    Exit?
                ┌────┴────┐
                NO         YES
                │           │
                └──→ Menu   END
```

## Progression

```text
MODULE 1
Sequence
│
├── Input
├── Variables
├── Data types
├── Expressions
└── Basic problem solving
        ↓
MODULE 2
Control flow
│
├── Conditions
├── Boolean logic
├── Decisions
├── Loops
└── Program tracing
        ↓
MODULE 3
Decomposition
│
├── Functions
├── Collections
├── Modules
└── More structured programs
```