# Module 5 - Version Control and Software Development Workflow

## What are we doing this week

In the previous modules, students learned how to write programs, structure them using functions and collections, work with files and modules, and handle errors.

So far, however, students have mainly worked on their programs as individuals.

Real software development requires more than writing code. Developers need to keep track of changes, understand what changed, recover previous versions, work on new features without breaking existing code, and collaborate with other developers.

This week, students will learn **version control with Git** and how GitHub can be used to store and collaborate on software projects.

The emphasis this week is not on memorizing Git commands. The emphasis is on understanding **why version control exists and how developers use it to manage changes to software**.

Students will learn how to:

* create a Git repository
* track changes to files
* create meaningful commits
* inspect the history of a project
* work with branches
* merge changes
* recover previous versions
* publish a repository to GitHub
* write useful project documentation
* follow a basic software development workflow

The goal is for students to stop thinking of a project as simply "a folder containing Python files" and begin thinking of it as a **software project with a history of changes**.

## Objectives

By the end of the week, students should be able to:

1. Explain what version control is and why developers use it.

2. Explain the difference between a working directory, staging area, and Git repository.

3. Initialize a Git repository.

4. Check the status of a Git repository.

5. Stage changes.

6. Create commits with meaningful commit messages.

7. View the history of a repository.

8. Identify which files have changed between versions.

9. Create and switch between branches.

10. Explain why branches are useful.

11. Merge a branch into another branch.

12. Identify and resolve a simple merge conflict.

13. Connect a local Git repository to GitHub.

14. Push changes to GitHub.

15. Clone an existing repository.

16. Write a useful README for a software project.

17. Use Git as part of a structured development workflow.

18. Make changes to an existing program without losing previous versions.

## Concepts

### 1. Version Control

* What version control means
* Why software projects need version control
* Tracking changes
* Project history
* Recovering previous versions
* Version control vs manually copying folders
* Local version control
* Distributed version control
* Git

### 2. Git Repository

* Working directory
* Git repository
* `.git`
* `git init`
* Repository status
* Tracked files
* Untracked files
* Modified files

### 3. Staging and Commits

* Staging area
* `git add`
* `git commit`
* Commit history
* `git log`
* Commit messages
* Small commits
* Meaningful commits

### 4. Reviewing Changes

* `git status`
* `git diff`
* Reviewing changes before committing
* Understanding what changed
* Comparing versions

### 5. Branches

* What a branch represents
* Why branches are useful
* Creating branches
* Switching branches
* Working independently
* `git branch`
* `git switch`

### 6. Merging

* Combining changes
* `git merge`
* Fast-forward merges
* Merge conflicts
* Why conflicts happen
* Identifying conflicting code
* Resolving a simple conflict
* Completing a merge

### 7. GitHub

* What GitHub is
* Local repository vs remote repository
* Creating a repository on GitHub
* Connecting a local repository to GitHub
* `git remote`
* `git push`
* `git pull`
* `git clone`

### 8. Project Documentation

* What a README is
* Why projects need documentation
* Project description
* Requirements
* Installation/setup
* How to run a program
* Example input/output
* Project structure
* Usage instructions

### 9. Basic Development Workflow

A simple development workflow:

```text
Problem
   ↓
Create/change code
   ↓
Test
   ↓
Review changes
   ↓
Commit
   ↓
Create branch for new feature
   ↓
Implement feature
   ↓
Test
   ↓
Merge
   ↓
Push to GitHub
```

## Activities

### 1. Review of Previous Modules

* Review the Student Management System
* Review modules and files
* Review functions
* Review collections
* Review file handling
* Review error handling
* Identify files that make up a software project

Students will examine their previous project and answer:

* What files are part of the program?
* Which files contain the main program?
* Which files contain reusable code?
* What would happen if an important file was accidentally deleted?
* How could we keep a history of changes?

### 2. Understanding Version Control

Students will compare two approaches to managing software.

Manual approach:

```text
student-management-v1/
student-management-v2/
student-management-final/
student-management-final-2/
student-management-final-real/
student-management-final-real-new/
```

Version control approach:

```text
student-management/
        │
        └── Git history
             │
             ├── commit 1
             ├── commit 2
             ├── commit 3
             └── commit 4
```

Students will discuss why Git is useful.

### 3. Creating a Repository

Students will:

* create a project folder
* initialize a Git repository
* inspect the repository
* create a `.gitignore`
* check repository status
* identify untracked files

### 4. Creating Commits

Students will:

* stage files
* create commits
* inspect commit history
* make another change
* create another commit
* compare the commits

Students will practice writing useful commit messages.

Bad:

```text
update
changes
fixed stuff
final
asdf
```

Better:

```text
Add student search functionality
Fix invalid score validation
Add student file persistence
```

### 5. Reviewing Changes

Students will modify an existing program and use Git to inspect the changes before committing them.

They will practice:

* `git status`
* `git diff`
* staging only intended files
* committing changes

### 6. Branching

Students will create a branch for a new feature.

For example:

```text
main
  │
  ├── add-student-search
  │
  └── add-student-deletion
```

Students will make changes on the feature branch without changing the main branch.

### 7. Merging

Students will merge a completed feature branch into the main branch.

They will observe how Git combines changes made in different parts of a project.

### 8. Merge Conflict Exercise

Students will deliberately create a simple conflict.

They will:

* create a branch
* change the same line of a file
* make a commit
* switch branches
* make a different change to the same line
* attempt a merge
* inspect the conflict
* resolve the conflict
* complete the merge

The objective is not to memorize conflict syntax.

The objective is to understand:

> Git cannot decide which change the developer wants, so the developer must decide.

### 9. GitHub

Students will:

* create a GitHub repository
* connect the local repository
* push the project
* inspect the repository online
* make another change locally
* push the change
* clone the repository into another directory

### 10. Project Workshop

Students will:

* choose a feature to add to their previous project
* create a feature branch
* implement the feature
* test it
* commit the changes
* merge the feature
* update the README
* push the completed project to GitHub

### 11. Code Review

Students will demonstrate their Git workflow.

They should be able to explain:

* what changed
* why they created a branch
* what each commit represents
* how they tested the change
* how the branch was merged
* what is currently on the main branch

---

# Exercises

Do the exercises in the `Exercises` folder in order.

The exercises progressively introduce version control, commits, change history, branching, merging, GitHub, and documentation.

The exercises should be completed before beginning the module project.

## Progression

```text
Understanding Version Control
          ↓
Git Repository
          ↓
Tracking Changes
          ↓
Staging
          ↓
Commits
          ↓
Viewing History
          ↓
Reviewing Changes
          ↓
Branches
          ↓
Merging
          ↓
Merge Conflicts
          ↓
GitHub
          ↓
Project Documentation
          ↓
SOFTWARE PROJECT
```

# Project

## Student Management System - Version 2

Students will return to the Student Management System developed in the previous modules.

The goal is to add a new feature while using Git to manage the development process.

Students must not simply modify the project directly on the `main` branch.

They must use a feature branch.

### Required Feature

Add a **student search feature**.

The program should allow the user to search for a student using the student's name or ID.

For example:

```text
Enter student ID: 1024

Student found.

Name: John
ID: 1024
Department: Computer Science
```

If the student does not exist:

```text
Student not found.
```

The exact structure should follow the student's existing Student Management System.

## Before You Code

Do not immediately modify the program.

First identify:

### Problem

What new capability is being added?

### Existing System

Which part of the existing program should change?

### Inputs

What information does the search feature require?

### Processing

How should the program search the existing student records?

### Outputs

What should happen when a student is found?

What should happen when a student is not found?

### Algorithm

Write the steps of the solution in plain English or pseudocode.

### Git Plan

Before making the change, create a feature branch.

For example:

```text
main
  ↓
add-student-search
```

The feature should be developed on the new branch.

## Git Requirements

The project must:

* be stored in a Git repository
* contain meaningful commits
* use a feature branch
* contain at least one commit for the feature
* merge the feature branch into `main`
* be pushed to GitHub
* contain a useful README
* contain a `.gitignore`

Students should make commits at meaningful points rather than committing every individual line change.

## README Requirements

The project README should contain:

1. What the program does
2. Features
3. How to run the program
4. Example input
5. Example output
6. Project structure
7. How the student search feature works
8. Any assumptions made
9. A brief description of the Git workflow used

## Testing

Test the project with different situations.

At minimum, test:

1. Searching for an existing student.

2. Searching for a student who does not exist.

3. Searching using different valid IDs or names.

4. Running the existing features after adding the new feature.

5. Invalid input where appropriate.

6. Confirming that existing functionality still works after the change.

## Git Testing

Students should also verify:

1. The project has a clean working tree after committing.

2. The feature exists on the feature branch.

3. The main branch does not contain the feature before merging.

4. The feature appears on the main branch after merging.

5. The GitHub repository contains the latest version.

## Bonus

Add another feature to the Student Management System using the same Git workflow.

Possible features include:

* deleting a student
* updating student information
* searching by department
* displaying all students in a department
* calculating a student's average score

The additional feature must also be developed on a separate branch and merged into `main`.


## Progression

```text
WEEK 1
Learn to write a program
        ↓
WEEK 2
Learn to control a program
        ↓
WEEK 3
Learn to structure a program
        ↓
WEEK 4
Learn to make a program persistent/reliable
        ↓
WEEK 5
Learn to manage a software project
```
