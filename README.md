# DSA-in-C

This repository (`DSA-in-C`) contains a simple implementation of a stack data structure in C programming language. The stack operations include push, pop, peek, and display.

Stack Implementation
--------------------

The stack is implemented using an array with a predefined maximum size (`max`). The operations are performed using functions and a menu-driven interface in the `main` function.

### File Structure

*  `https:/github.com/rashmi-992/stack_using_array.c/1.Stack`: Contains the main menu-driven program.
*   `README.md`: Documentation for the code in Markdown format.

### Code Structure

#### Constants

```c
#define max 5
```
*   Defines the maximum size of the stack array.

#### Global Variables

```c
int arr[max]; int top = -1; int item;
```

*   `arr`: Array to store stack elements.
*   `top`: Keeps track of the top of the stack.
*   `item`: Temporary variable to store user input.

#### Functions

1.  `push()`: Adds an element to the top of the stack.
2.  `pop()`: Removes the element from the top of the stack.
3.  `peek()`: Displays the top element of the stack without removing it.
4.  `display()`: Displays all elements in the stack.

#### Main Function

```c
int main()
```

*   The main menu-driven program that allows users to interact with the stack.

### User Interface

Users can select options from the menu to perform stack operations:

1.  **Push**: Adds an element to the stack.
2.  **Peek**: Displays the top element of the stack.
3.  **Pop**: Removes the top element from the stack.
4.  **Display**: Shows all elements in the stack.

### Handling Overflow and Underflow

*   **Overflow**: Occurs when trying to push an element onto a full stack.
*   **Underflow**: Occurs when trying to pop or peek an element from an empty stack.

Usage
-----

1.  Clone the repository: `git clone https://github.com/rashmi-992/DSA-in-C.git`
2.  Compile and run the program using a C compiler.
3.  Follow the on-screen menu to interact with the stack.

* * *
