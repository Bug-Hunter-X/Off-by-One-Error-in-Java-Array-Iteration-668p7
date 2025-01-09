# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error occurs due to an incorrect loop condition that attempts to access an array element beyond its bounds.

## How to Reproduce

1. Clone the repository.
2. Compile and run `bug.java`. Observe the `ArrayIndexOutOfBoundsException`. 
3. Compile and run `bugSolution.java` to see the correct output.

## Lesson Learned

Pay close attention to loop conditions when working with arrays. Remember that array indices start at 0 and go up to `array.length - 1`.