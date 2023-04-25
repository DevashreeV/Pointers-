# Pointers-
 

 In an array A pointer is a type of variable that holds as its value the memory address of another type of variable.

The * operator creates a pointer variable, which points to a data type (like an int) of the same type.

The pointer is given the address of the variable you are working with

Basic Syntax is given by:

datatype * pointer_name;

![image](https://user-images.githubusercontent.com/91966097/234310203-27c45583-d1bc-405d-920d-11048c9817ea.png)


1.Address of Operator:

The addressof operator ( & ) is a unary operator that returns the address of its operand. Its operand can be a variable, function, array, structure, etc.

&variable_name;

2.Dereferencing Operator:

The dereference operator ( * ), also known as the indirection operator is a unary operator. It is used in pointer declaration and dereferencing.

3. Declaring a pointer:

To declare a pointer, use the * symbol before the pointer name. For example, int* ptr; declares a pointer named ptr that can hold the memory address of an integer variable.

4.Assigning a value to a pointer:

The address of a variable may be obtained by using the & operator to assign a value to a pointer. For instance, int var = 10; int* ptr = &var; gives the pointer ptr the memory location of var.

Basic Example of a pointer:




