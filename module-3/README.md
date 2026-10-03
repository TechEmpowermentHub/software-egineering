# Module 3 - Functions, Collections and Program Structure

## What are we doing this week

In the first two weeks, students learned how to write programs that process information, make decisions, and repeat actions.

As programs become larger, putting everything into one long sequence of instructions becomes difficult to understand, test, and maintain.

This week, students will learn how to **break programs into smaller reusable pieces using functions** and how to **store and work with multiple pieces of related information using collections**.

The emphasis this week is on organizing programs so that they are easier to understand, reuse, and extend.

## Objectives

By the end of the week, students should be able to:

1. Explain why functions are useful in software development.

2. Define and call functions.

3. Use parameters to provide information to functions.

4. Use return values to get results from functions.

5. Distinguish between printing a result and returning a result.

6. Understand basic variable scope.

7. Create and manipulate lists.

8. Access, modify, and add items to lists.

9. Loop through collections.

10. Use dictionaries to represent structured information.

11. Combine functions, conditionals, loops, and collections.

12. Break a larger problem into smaller functions.

13. Organize a program into logical components.

## Concepts

### 1. Functions

* Why functions are useful
* Defining functions
* Calling functions
* Function names
* Function parameters
* Arguments
* Return values
* `return`
* Functions that perform actions
* Functions that calculate and return results

### 2. Scope

* Local variables
* Variables outside functions
* How information moves into and out of functions
* Avoiding unnecessary global variables

### 3. Lists

* Creating lists
* Accessing items
* Indexes
* Changing items
* Adding items
* Removing items
* List length
* Looping through lists

### 4. Dictionaries

* Key-value pairs
* Creating dictionaries
* Accessing values
* Adding values
* Updating values
* Removing values
* Looping through dictionaries

### 5. Program Decomposition

* Breaking a problem into smaller parts
* Identifying responsibilities
* Designing functions around responsibilities
* Passing information between functions
* Combining functions into a larger program
* Avoiding unnecessarily large functions

## Activities

### 1. Review of Previous Concepts

* Review variables
* Review input and output
* Review conditionals
* Review loops
* Review problem decomposition using inputs → processing → outputs

### 2. Understanding Functions

* Why functions exist
* Define and call functions
* Add parameters
* Return values
* Trace function execution
* Compare `print()` and `return`

### 3. Guided Programming Exercises

* Simple functions
* Functions with parameters
* Functions with multiple parameters
* Functions that return values
* Functions containing conditionals
* Functions containing loops
* Lists
* Looping through lists
* Dictionaries
* Combining functions and collections

### 4. Program Decomposition Exercise

Students will take a larger problem and identify:

* The major tasks the program needs to perform
* Which tasks should become functions
* What information each function needs
* What each function should return
* What data should be stored in collections

They will then write the solution in plain English or pseudocode before implementing it.

### 5. Project Workshop

* Design the Student Management System
* Identify the information that needs to be stored
* Decide which collections are required
* Identify the program's functions
* Implement the functions
* Combine the functions into the application
* Test different scenarios
* Debug problems
* Refactor repetitive or unclear code
* Commit the project to Git

### 6. Code Review

* Students demonstrate their programs
* Discuss how their programs were decomposed
* Review function responsibilities
* Review use of lists and dictionaries
* Identify unnecessarily complicated code
* Identify duplicated logic
* Discuss possible improvements

## Exercises

Do the exercises in the [Exercises folder](./exercises/) in order.

The exercises progressively introduce functions, collections, and program decomposition. Students should complete them before beginning the module project.

## Project

**Student Management System**

Build a command-line program that allows a user to manage a collection of students.

The program should allow the user to:

* Add a student
* View students
* Find a student
* Record a student's score
* Calculate a student's average score
* Exit the program

Students should first identify the information the program needs to store, decide how that information should be represented, and break the program into functions before writing the Python code.

```text
WEEK 1 — SEQUENCE

Input
  ↓
Process
  ↓
Output


WEEK 2 — CONTROL FLOW

Input
  ↓
Decision ─────┐
  ↓           │
Process       │
  ↓           │
Repeat ←──────┘


WEEK 3 — STRUCTURE

             Program
                │
       ┌────────┼────────┐
       ↓        ↓        ↓
   Function  Function  Function
       │        │        │
       └────────┼────────┘
                ↓
            Collections
          ┌─────┴─────┐
        Lists      Dictionaries
```