# Module 4 - Files, Errors, and Modules

## What we are doing this week

In the first three weeks, students learned how to write programs that process information, make decisions, repeat actions, and organize logic using functions and collections.

However, the programs they have built so far have two important limitations.

First, when the program stops running, the information stored in variables and collections is lost.

Second, as programs become larger, keeping all of the code in one file makes the program harder to understand and maintain.

This week, students will learn how to **save information to files, handle problems that occur while a program is running, and organize programs across multiple files using modules**.

The emphasis this week is on building programs that are more **persistent, reliable, and organized**.

Students will also learn how structured data can be stored using formats such as **JSON and CSV**, and how to handle situations such as invalid user input, missing files, and other runtime errors.

By the end of the week, students should be able to take the Student Management System from Week 3 and turn it into an application that can **save and load its data between program runs**.

## Objectives

By the end of the week, students should be able to:

* Explain why programs need to store data outside of memory.
* Read information from a text file.
* Write information to a text file.
* Understand how files are opened, read, written, and closed.
* Use with open() to work safely with files.
* Explain what a module is and why modules are useful.
* Create and import their own Python modules.
* Organize related functions into separate files.
* Store structured data using JSON.
* Read and write JSON data using Python.
* Read and write CSV data.
* Explain what an exception is.
* Handle common runtime errors using try and except.
* Validate user input and respond appropriately to invalid input.
* Combine functions, collections, files, modules, and error handling.
* Build a program whose data persists after the program exits.
* Organize a multi-file Python program into logical components.

## Concepts

1. Modules
* What a module is
* Why modules are useful
* Creating a Python module
* Importing a module
* Importing specific functions
* Using functions from another file
* Separating responsibilities across files
* Organizing a larger program

2. Working with Files
* What files are used for
* File paths
* Opening files
* Reading files
* Writing files
* Appending to files
* Closing files
* Using with open()
* Text files
* File-related errors

3. Structured Data
* Why structured data is useful
* JSON
* JSON objects and arrays
* Python dictionaries and JSON objects
* Python lists and JSON arrays
* Converting Python data to JSON
* Reading JSON into Python
* Writing JSON to a file
* CSV files
* Rows and columns
* Reading CSV data
* Writing CSV data

4. Exceptions and Errors
* What runtime errors are
* What an exception is
* Common Python exceptions
* ValueError
* ZeroDivisionError
* FileNotFoundError
* try
* except
* Handling errors without crashing the program
* Giving useful error messages
* Distinguishing between expected errors and programming bugs

5. Input Validation
* Why user input cannot always be trusted
* Validating numbers
* Handling invalid conversions
* Checking acceptable ranges
* Handling missing files
* Handling invalid data
* Asking the user to try again

6. Program Organization

* Separating responsibilities
* Identifying which functions belong together
* Creating modules around responsibilities
* Importing functionality between modules
* Keeping the main program focused on application flow
* Combining modules with functions and collections
* Avoiding unnecessarily large files

7. Persistent Programs
* Temporary data vs persistent data
* Loading data when a program starts
* Saving data when a program changes
* Saving data before a program exits
* Handling the first run when no data file exists
* Designing programs around stored data

## Activities

1. Review of Previous Concepts
* Review variables
* Review lists
* Review dictionaries
* Review functions
* Review parameters and return values
* Review loops and conditionals
* Review program decomposition
* Review the Student Management System from Week 3

Students will identify an important limitation of the previous project:

What happens to the students when the program is closed?

This question introduces the need for persistent data.

2. Understanding Files

* Why programs need files
* Create a text file
* Write information to a file
* Read information from a file
* Append information to a file
* Use with open()
* Work with file paths
* Handle a missing file

Students will begin by working with simple text files before moving to structured formats.

3. Understanding Modules
* What happens when a program grows beyond one file
* Create a separate Python file
* Define functions inside the module
* Import the module
* Import individual functions
* Use imported functions
* Decide which functions belong together

Students will reorganize simple programs into multiple files and observe how modules make larger programs easier to manage.

4. Working with Structured Data

Students will move from simple text files to structured data.

* Store dictionaries as JSON
* Store lists of dictionaries as JSON
* Load JSON data
* Modify JSON data
* Save JSON data
* Read CSV files
* Process rows from a CSV file
* Compare JSON and CSV

Students will examine why the choice of storage format depends on the kind of data being stored.

5. Understanding Errors and Exceptions

Students will intentionally create situations that cause programs to fail.

Examples include:

* Entering text when a number is expected
* Dividing by zero
* Opening a file that does not exist
* Entering an invalid menu option

They will then learn how to use try and except to handle expected runtime problems.

The emphasis is not simply on preventing errors, but on understanding what went wrong, where it happened, and how the program should respond.

6. Input Validation Exercise

Students will build programs that repeatedly ask for information until valid input is provided.

They will practice:

* Converting input safely
* Checking valid ranges
* Handling invalid input
* Displaying useful messages
* Repeating the request when necessary

This connects error handling with the control-flow concepts learned in Week 2.

7. Program Decomposition Exercise

Students will take a program that has become too large and identify which responsibilities should be separated.

They will identify:

* The main application logic
* Functions responsible for managing data
* Functions responsible for reading and writing data
* Functions responsible for displaying information
* Functions responsible for validation

They will then decide which responsibilities belong in separate modules.

8. Project Workshop

Students will upgrade the Student Management System from Week 3.

They will:

* Review the existing program
* Identify the data that needs to persist
* Choose JSON as the storage format
* Design the file structure
* Create a storage module
* Create a student management module
* Load students when the program starts
* Save students when data changes
* Handle a missing data file
* Handle invalid user input
* Handle invalid JSON data
* Test different scenarios
* Debug problems
* Refactor unclear code
* Commit the project to Git

9. Code Review
* Students demonstrate their programs
* Review how responsibilities were divided between modules
* Review file handling
* Review JSON structure
* Review error handling
* Identify duplicated logic
* Identify unnecessarily large functions
* Discuss how the program behaves when something goes wrong
* Discuss possible improvements


## Exercises

Do the exercises in the Exercises folder in order.

The exercises progressively introduce modules, file handling, structured data, exceptions, and persistent programs.

Students should complete the exercises before beginning the module project.

## Project

Persistent Student Management System

Upgrade the Student Management System from Week 3 so that student information is saved and available the next time the program runs.

The program should allow a user to:

* Add a student
* View students
* Find a student
* Calculate the average score
* Exit the program

The important difference is that student information should no longer disappear when the program stops.

When the program starts, it should load previously saved students.

When students are added or changed, the program should save the updated information.

The project should also be divided into multiple modules so that different parts of the program have clear responsibilities.

For example:

module-4/
└── project/
    ├── main.py
    ├── student_manager.py
    ├── storage.py
    ├── students.json
    └── README.md

Students should first identify:

* What data needs to be stored
* How the data should be represented
* Where the data should be stored
* Which functions are needed
* Which responsibilities belong in each module
* What errors can occur
* How those errors should be handled

They should then write the solution in plain English or pseudocode before implementing it in Python.

```text
WEEK 4 — ORGANIZATION + PERSISTENCE

                Program

                   │

          ┌────────┼────────┐
          ↓        ↓        ↓

       Module   Module    Module

          │        │        │
          └────────┼────────┘
                   ↓
              Application
                   │
                   ↓
              Persistent Data
                   │
             ┌─────┴─────┐
             ↓           ↓
           JSON         CSV
                  

              + Error Handling

                   ↓

             Reliable Program
```

Week 4 therefore builds on the first three weeks:

Week 1 — Sequence:
Students learn to make a program execute instructions.

Week 2 — Control Flow:
Students learn to make programs make decisions and repeat actions.

Week 3 — Structure:
Students learn to organize logic using functions and collections.

Week 4 — Organization + Persistence:
Students learn to organize larger programs across modules, save information to files, and handle problems without the program unnecessarily crashing.
