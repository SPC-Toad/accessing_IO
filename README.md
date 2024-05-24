# Input and Output Through Assembly

This project demonstrates how to access and handle input and output operations using assembly language. The project includes an assembly file, a C program for testing, and a makefile for building the project.

## Project Structure

- `echo.s`: The assembly source file containing the implementation of input and output operations.
- `echo.syms`: Symbol file for the assembly program.
- `echoc.c`: A C program that interacts with the assembly code to perform I/O operations.
- `syms`: Additional symbols required by the assembly code.
- `makefile`: Makefile for building the project.

## Prerequisites

- GCC (GNU Compiler Collection)
- Make utility

## Building the Project

To build the project, navigate to the project directory and run the following command:

```sh
make
```

This will compile the assembly and C code, linking them together to create an executable.

## Running the Program

After building the project, you can run the executable to see the input and output operations in action:

```sh
./echo
```

## File Descriptions

### echo.s

The `echo.s` file contains the assembly code that handles input and output operations. This includes reading from standard input and writing to standard output.

### echo.syms

The `echo.syms` file includes symbols that are referenced by the assembly code in `echo.s`.

### echoc.c

The `echoc.c` file is a C program that demonstrates how to call the assembly functions defined in `echo.s`. It provides a simple interface to test the I/O functionality.

### syms

The `syms` file contains additional symbols required by the assembly code. 

### makefile

The `makefile` automates the build process, compiling the assembly and C source files, and linking them to produce the final executable.

## Example Usage

The following example shows how to compile and run the program:

```sh
make
./echo
```

You will be prompted to enter input, which will be processed by the assembly code and then echoed back to the standard output.
