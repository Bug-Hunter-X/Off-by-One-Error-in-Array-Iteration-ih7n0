# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating through arrays.  The error occurs when the loop condition includes an index equal to the array's length, leading to an attempt to access an element beyond the array's bounds. This results in an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

This example highlights the importance of careful loop boundary checks when working with arrays in Java.