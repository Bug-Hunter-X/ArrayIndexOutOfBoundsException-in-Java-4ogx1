# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `BuggyArray.java` file contains code that attempts to access an array element beyond its valid index range.  The `FixedArray.java` file provides a corrected version.

The error is caused by using a loop condition `i <= arr.length`, which includes an index outside the array's bounds (0 to 4).  Correct index access is crucial for preventing this type of runtime exception.

This example highlights the importance of careful array indexing in Java programming. Always ensure that your loop conditions and array access indices are within the valid range to avoid unexpected errors.