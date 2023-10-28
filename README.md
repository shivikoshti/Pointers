# Pointers
## Theory:
Pointers are symbolic representations of addresses. They enable programs to simulate call-by-reference as well as to create and manipulate dynamic data structures. 
Iterating over elements in arrays or other data structures is one of the main use of pointers. 
The address of the variable you’re working with is assigned to the pointer variable that points to the same data type (such as an int or string).<br>
#### Syntax:
datatype *var_name; <br>
int *ptr;   // ptr can point to an address which holds int data<br>
The reason we associate data type with a pointer is that it knows how many bytes the data is stored in. When we increment a pointer, we increase the pointer by the size of the data type to which it points.
