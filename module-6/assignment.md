# Assignment

Complete all exercises independently and submit the repaired Student Management System.

Your submission should contain:

```text
module-6/

├── exercises/
│   ├── 1-syntax-error.py
│   ├── 2-runtime-error.py
│   ├── 3-read-traceback.py
│   ├── ...
│   └── 12-debug-broken-program.py
│
└── project/
    ├── student-management-system/
    │   ├── ...
    │   ├── README.md
    │   ├── BUGS.md
    │   └── tests.md
    │
    └── README.md
```

## Project Requirements

You must:

1. Run the broken Student Management System before making changes.
2. Identify and document the problems you discover.
3. Reproduce each significant problem.
4. Explain the expected behavior.
5. Explain the actual behavior.
6. Identify the cause of each bug.
7. Fix the bugs.
8. Test the repaired program.
9. Perform regression testing on existing functionality.
10. Record the bug fixes using Git.

## BUGS.md

Your BUGS.md file should document the problems you found.

For each bug, include:

## Bug

### Problem

What went wrong?

### How to Reproduce

What steps cause the problem?

### Expected Behavior

What should happen?

### Actual Behavior

What actually happened?

### Cause

Why did the problem happen?

### Fix

What did you change?
Testing

Your test plan should include:

## Normal Cases
* Normal student data
* Normal scores
* Existing student searches
* Normal file operations

## Boundary Cases
* Score of 0
* Score of 100
* Empty student list
* First/last student
* Minimum and maximum expected values
* Invalid Cases
* Invalid menu choice
* Invalid score
* Missing student
* Invalid search
* Invalid file/data where appropriate

## Regression Tests

Verify that previously working features still work after the bug fixes.

Create:

`tests.md`

containing:

Test
Input
Expected Result
Actual Result
Status

## Git Requirements

Bug fixes must be managed using Git.

Create a branch for the work:

```text
main
  ↓
fix/student-management-bugs
```

Commit meaningful changes.

For example:

Fix student search error
Fix score calculation
Handle missing student records
Fix file loading

Do not commit messages such as:

fix
update
changes
final

After testing:

1. Merge the bug-fix branch into main.
2. Run the regression tests again.
3. Push the final project to GitHub.

## Bonus

Write automated tests using Python's unittest module.

Create:

```text
tests/
    test_student_management.py
```

Write tests for at least three functions.

For example:

```python
calculate_average()
calculate_grade()
find_student()
```

The tests should verify expected behavior automatically.

Submission Checklist

Before submitting, confirm:

- [ ] The program runs.
- [ ] Significant bugs have been identified.
- [ ] Bugs are documented in BUGS.md.
- [ ] Each bug has been reproduced.
- [ ] The cause of each bug is explained.
- [ ] Bugs have been fixed.
- [ ] Normal inputs have been tested.
- [ ] Boundary inputs have been tested.
- [ ] Invalid inputs have been tested.
- [ ] Regression testing has been performed.
- [ ] Existing functionality still works.
- [ ] Git was used to manage the bug fixes.
- [ ] Meaningful commits were created.
- [ ] The project has been pushed to GitHub.
- [ ] The project README has been updated.