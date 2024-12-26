# Uncommon Java Loop Control Bug: Premature Termination

This repository demonstrates a subtle bug related to loop control flow in Java. The `BuggyLoop.java` file contains code with a `while` loop that uses a `break` statement.  This `break` statement, although seemingly simple, can lead to unexpected behavior if not carefully considered within the context of nested loops or more complex conditions.  The corrected version, `FixedLoop.java`, illustrates how to manage loop termination more effectively.

## Problem

The `BuggyLoop.java` code intends to print numbers from 0 to 9, but unexpectedly stops at 4, due to the `break` statement that terminates the loop prematurely.