## FUNCTIONS
``` c
In C, a function is a named block of code that performs a specific task and can be called from different parts of a program.
Functions are essential in programming as they help in organizing the code, making it modular, and promoting code reusability.

Here's the general syntax of a function in C:
return_type function_name(parameter_list) {
    // Function body (code)
    // ...
    // ...
    return value; // Optional return statement with the return type specified earlier
}

Let's break down the different components:

1.return_type: This is the data type of the value that the function returns. It can be any valid C data type, including int, float, double, char, void, etc.
If the function doesn't return anything, you use the void keyword.

2.function_name: This is the identifier or name of the function. It follows the rules for variable naming in C.

3.parameter_list: This is a list of input parameters that the function accepts. Parameters are variables that are used inside the function to perform its task.
The list is enclosed in parentheses and can be empty if the function takes no parameters.
Function body: This is the block of code that defines what the function does. I
t contains the statements and instructions that will be executed when the function is called.

4.return value: This is an optional statement used to return a value from the function.
It is only applicable for functions with a non-void return type.
If the function doesn't need to return anything or doesn't reach this statement, you can omit it.

Here's an example of a simple C function that adds two integers and returns the result:

#include <stdio.h>

int add(int a, int b) {
    int result = a + b;
    return result;
}

int main() {
    int num1 = 5;
    int num2 = 10;
    int sum = add(num1, num2);
    printf("The sum is: %d\n", sum);
    return 0;
}
In this example, the add function takes two parameters (a and b) of type int and returns their sum.
The main function calls the add function and prints the result. Output: The sum is: 15

```
