# simple_calculator

Function Definitions:

add(x, y): Takes two numbers as parameters and returns their sum.
subtract(x, y): Takes two numbers as parameters and returns the result of subtracting the second from the first.
multiply(x, y): Takes two numbers as parameters and returns their product.
divide(x, y): Takes two numbers as parameters and returns the result of dividing the first by the second. It checks for division by zero and handles the error.


Main Calculator Function (calculator()):

Prints a simple menu with options for arithmetic operations: addition, subtraction, multiplication, and division.
Takes user input for the choice of operation (choice), as well as two numbers (num1 and num2).
Based on the user's choice, it calls the corresponding arithmetic function and stores the result in the variable result.
Prints the result.


Main Block (`if name == "main":):

Calls the calculator() function when the script is executed.


Execution:

Users run the script, and it prompts them to choose an operation (1/2/3/4) and enter two numbers.
The chosen arithmetic operation is performed, and the result is displayed.
The program handles division by zero, providing an error message in such cases.
