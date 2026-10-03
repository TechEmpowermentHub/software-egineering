# 9 - Boundary Testing

**Goal:** Learn to test values around boundaries.

A school grading program uses:

```text
70 - 100 → A
60 - 69  → B
50 - 59  → C
45 - 49  → D
40 - 44  → E
0 - 39   → F
```

Create a test plan.

At minimum, test:

```text
0
1
39
40
41
44
45
46
49
50
51
59
60
61
69
70
71
99
100
```

Also test:

```text
-1
101
```

##Requirements
* File: 9-boundary-testing.py
* Create the grading function.
* Create the test cases.
* Record the expected result for each.
* Run the program.
* Compare expected and actual results.

The objective is to demonstrate why testing only one value from each range is not enough.
