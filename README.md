# Pointers
## Theory:a pointer is a special variable that holds the memory address of another variable. This memory address points to the location where the variable's value is stored in the computer's memory. Pointers enable direct manipulation of memory, allowing for advanced memory management and efficient data handling. They are declared using an asterisk (*) and can be used to dynamically allocate memory, work with arrays, and even store the address of functions. While powerful, pointers require careful handling to avoid common issues like memory leaks and undefined behavior, making them a fundamental but potentially tricky aspect of C++ programming.<br>
#### Syntax:
datatype *var_name; <br>
int *ptr;   // ptr can point to an address which holds int data<br>
The reason we associate data type with a pointer is that it knows how many bytes the data is stored in. When we increment a pointer, we increase the pointer by the size of the data type to which it points.
