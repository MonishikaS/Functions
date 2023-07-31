```c
In C, a function has two parts: declaration and definition. These parts serve different purposes and are usually separated to allow for modular programming.

Function Declaration:
The declaration of a function tells the compiler about the function's existence, its name, return type, and the types of parameters it expects (if any).
It does not contain the actual implementation (body) of the function.
 Function declarations are typically placed in header files (with a .h extension) and are used to provide information about the functions to other parts of the program that need to use them.

The general syntax of a function declaration is:
return_type function_name(parameter_list);

Here's an example of a function declaration for the add function:
int add(int a, int b);

Function Definition:
The definition of a function provides the actual implementation or body of the function.
It contains the statements and instructions that define what the function does.
The function definition includes the complete function declaration, but it also includes the code inside the function.

return_type function_name(parameter_list) {
    // Function body (code)
    // ...
    // ...
    return value; // Optional return statement with the return type specified earlier
}

Here's the definition of the add function from our previous example:
int add(int a, int b) {
    int result = a + b;
    return result;
}

Note that the function definition includes the return type (int), the function name (add), and the parameter list (int a and int b).
The body of the function contains the code that adds the two parameters a and b and returns the result.

To use a function in your program, you need to provide its declaration before calling it.\
This allows the compiler to understand the function's signature (return type and parameter types) before it is actually used in the program.
Then, you can include the definition (implementation) of the function in your source file, or you may link to its implementation if it resides in a separate compiled file (e.g., a .c file containing the function's code).

