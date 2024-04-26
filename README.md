# Null Pointer Handling in C++

## Introduction

This C++ code demonstrates how to handle null pointers in C++ using the nullptr keyword. It includes functions to process a pointer, create and return a null pointer, and test the behavior of null pointers.

## Usage

1. Compile the code using a C++ compiler.

2. Run the compiled executable to observe the output.

## Code Description

- **cppnullptr.cpp**: This file contains the main code for testing null pointers.

- The `processPointer` function takes an int pointer as input and checks if it's a null pointer or not.

- The `createNullPointer` function returns a null pointer.

- In the `main` function, a null pointer is created and tested using the ternary operator.

- The null pointer is passed to the `processPointer` function to test its behavior.

- A null pointer is returned from the `createNullPointer` function and checked in the `main` function.

## Example Output

```cpp
Test Pointer  : Pointer is nullptr.
Test Pointer  : Passed null pointer.
Test Pointer  : Received null pointer.
```

## Additional Notes

- The code demonstrates how to handle null pointers safely in C++ using the nullptr keyword.

- It provides examples of creating, passing, and returning null pointers.