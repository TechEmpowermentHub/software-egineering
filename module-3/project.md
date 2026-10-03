# Project - Student Management System

The exercises in this module have progressively introduced the capabilities required for this project.

You will now combine them into a single program.

## Problem

Build a command-line Student Management System.

The program should allow a user to manage information about multiple students.

Each student should have:

* Name
* Age
* Score

You should represent each student using a dictionary and store the students in a list.

The program should display a menu:

```text
1. Add student
2. View students
3. Find student
4. Calculate average score
5. Exit
```

## Add Student

Ask the user for:

* Student name
* Student age
* Student score

Then add the student to the collection.

Example:

```text
Student name: Kelechi
Age: 20
Score: 75

Student added successfully.
```

## View Students

Display all students currently stored in the system.

Example:

```text
Students:

1. Kelechi - Age: 20 - Score: 75
2. Ada - Age: 19 - Score: 82
3. Emeka - Age: 21 - Score: 68
```

## Find Student

Ask the user for a student's name.

If the student exists, display their information.

If the student does not exist, display an appropriate message.

Example:

```text
Enter student name: Ada

Name: Ada
Age: 19
Score: 82
```

## Calculate Average Score

Calculate and display the average score of all students.

Example:

```text
Average score: 75.0
```

## Exit

Display an appropriate message and end the program.

The menu should continue appearing until the user chooses to exit.

## Before You Code

Do not begin by writing Python.

First identify:

### Data

What information does the program need to store?

How will each student be represented?

How will multiple students be stored?

### Functions

What tasks does the program need to perform?

For example:

```text
add_student()
view_students()
find_student()
calculate_average()
display_menu()
```

These are suggestions, not requirements. You should decide how to structure your own program.

### Inputs

What information does the program receive?

### Processing

What operations need to happen?

### Outputs

What information should the program display?

### Algorithm

Write the steps of the solution in plain English or pseudocode.

### Program Structure

Identify the main functions and what each function is responsible for.

Only after doing this should you begin writing the Python program.

## Requirements

Your program must use:

* Variables
* User input
* Type conversion
* Conditional statements
* Loops
* Functions
* Parameters
* Return values where appropriate
* Lists
* Dictionaries

The program should:

* Add students.
* Store multiple students.
* Display students.
* Find students.
* Calculate the average score.
* Continue operating until the user chooses to exit.
* Use functions to organize the program.
* Keep functions focused on specific responsibilities.
* Display clear messages to the user.

## Testing

Test your program with different situations.

At minimum, test:

1. Adding one student.
2. Adding multiple students.
3. Viewing students.
4. Finding an existing student.
5. Searching for a student that does not exist.
6. Calculating the average with multiple students.
7. Using the program with no students.
8. Exiting the program.

## Bonus

Add additional functionality.

For example:

* Find the student with the highest score.
* Find the student with the lowest score.
* Calculate the average age.
* Allow a student's score to be updated.
* Delete a student.
* Display students who scored above a particular value.

Do not add bonus features until the required functionality works correctly.
