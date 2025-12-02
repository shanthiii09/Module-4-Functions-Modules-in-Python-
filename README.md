# Module-4-Functions-Modules-in-Python-

In Task 1: 

A function named factorial is defined. It takes one number n as input.

Inside the function, the code first checks if n is equal to 0.

If n is 0, the function returns 1 (this is the base case of factorial).

If n is not 0, the function returns n * factorial(n - 1) — this is where recursion happens.

The program then asks the user to enter a number.

The user’s input is converted into an integer and stored in the variable num.

The function factorial(num) is called using the value given by the user.

The function keeps calling itself with smaller values until it eventually reaches 0.

Once the base case is hit, all the pending multiplications are solved as the program returns back through each call.

Finally, the program prints the factorial result to the user.

In Task 2: 

The program starts by importing everything from the math module using from math import *.
This gives access to functions like sqrt, log, and sin without writing math. before them.

The user is asked to enter a number, and the input is stored in the variable a.

The input is converted into an integer so mathematical operations can be performed correctly.

sqrt(a) is used to calculate the square root of the number.

log(a) calculates the natural logarithm (log base e) of the number.

sin(a) calculates the sine of the number, treating it as radians.

Each calculated value is printed one after another with a clear label.

The program ends after displaying all three mathematical results.
