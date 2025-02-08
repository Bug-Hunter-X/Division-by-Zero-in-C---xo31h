# Division by Zero Bug in C++

This repository demonstrates a common runtime error in C++: division by zero.  The `bug.cpp` file contains code that attempts to divide by zero, leading to undefined behavior and a potential crash. The `bugSolution.cpp` file provides a corrected version that handles potential division-by-zero scenarios.

**Bug:**
Division by zero is a frequent source of errors in programming.  In this example, the variable `y` is initialized to 0, causing a division-by-zero error when the program attempts to calculate `x / y`. This will typically result in a runtime exception or program termination.

**Solution:**
The solution involves adding a check to prevent division by zero. If the divisor (`y`) is zero, the program should handle this gracefully, perhaps by returning an error code, using a default value, or taking other appropriate actions.