# 10 — Solving a Real Problem

**Goal:** Design a small persistent application using the concepts learned in this module.

A small shop needs a program for keeping track of its products.

Each product should have:

* name
* price
* quantity

The program should allow the user to:

* Add a product
* View products
* Save products
* Load products
* Exit

The products should be stored in a JSON file so that they are still available when the program is run again.

Before writing Python code, identify:

### Data

What information needs to be stored?

How should each product be represented?

How should multiple products be represented?

### Functions

What tasks does the program need to perform?

Which tasks should become functions?

### Files

What information needs to be saved?

What information needs to be loaded?

What file format should be used?

### Errors

What could go wrong?

For example:

* The data file does not exist.
* The user enters an invalid price.
* The user enters an invalid quantity.
* The JSON file contains invalid data.


### Inputs

What information does the program receive?

### Processing

What operations need to happen?

### Outputs

What information should the program display?

### Algorithm

Write the steps of the solution in plain English or pseudocode.

### Program Structure

Identify the modules and functions the program will need.

Only after completing this planning should you begin writing the Python program.

## Requirements
* File: 10-solving-a-real-problem.py
* Use functions.
* Use a separate module where appropriate.
* Use a list and dictionaries.
* Read data from a JSON file.
* Write data to a JSON file.
* Handle missing files.
* Handle invalid user input.
* Use exception handling where appropriate.
* Keep functions focused on specific responsibilities.
* Test the program with different inputs.