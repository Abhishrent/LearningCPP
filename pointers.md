### Pointers
 **Main Concept: Each variable intialization (for example, int x = 4) creates a memory block in the memory of the same name (here x) that can hold a certain value (here 4) and has a certain address (some hex address)**

 A pointer points to the address of a memory block. 

```cpp
int x = 4;
int *px = &x;
int y = *px;

cout<<y;

------------------------------------------
OUTPUT:
4
```
**Explanation**

`int x = 4;`  
This line creates a variable x of type int that is set to the value 4.  

`int *px = &x;`  
This line creates a pointer variable that points to the address of variable x.
A [variable_type] followed by the [variable_name] with a star (*) in front denotes that it is indeed a pointer variable being initialized.


`int y = *px;`  
This line fetches the value stored in the memory block that the pointer *px points to and stores it into variable y. If we are to print y, it displays 4 according to our example.

