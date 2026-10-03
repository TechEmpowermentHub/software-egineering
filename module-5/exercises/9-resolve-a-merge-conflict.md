# 9 - Resolve a Merge Conflict

**Goal:** Understand what happens when Git cannot automatically combine changes.

Create a new branch:

```text
change-message
```

Change the same line of code that will also be changed on main.

Commit the change.

Switch to `main`.

Make a different change to the same line.

Commit it.

Now attempt to merge the branch.

Git should report a merge conflict.

## Your task

Resolve the conflict manually.

Then:

1. Check the file.
2. Decide which version of the code should remain.
3. Remove the conflict markers.
4. Test the program.
5. Complete the merge.


## Questions

1. Why did Git report a conflict?
2. What decision did you have to make?
3. Why can't Git always automatically decide which change is correct?
