# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The `bug.java` file contains code that attempts to access an array element beyond its bounds, leading to this exception.  The solution is provided in `bugSolution.java`, which correctly handles array access to prevent the error.

The exception occurs because Java arrays are zero-indexed.  Attempting to access `arr[5]` in an array of size 5 is incorrect as the valid indices range from 0 to 4. This is a frequent mistake among beginners and experienced programmers alike, especially when handling arrays of unknown or dynamically determined sizes.

This example serves as a reminder to always carefully check array bounds before accessing elements, using techniques such as checking the array length (`arr.length`) before accessing any element.