```
# PES Project 1
# Authors: Suman Hosmane & Mohit Rane
# Goal: Create a memory tool that performs various functions which are mentioned in the details below.
# This code was built by my team from the scratch for the first project in the Principle of Embedded Software course.
```

This project demonstrates how to use a Makefile to consolidate various .c and .h file into a single project or a single main.c file.
The code is designed to be menu driven, however a single command line parameter is also accepted and will not crash the code.
We have various functionalities incorporated in the project, listed below:

>-**help**

help command invokes the help function which tells the user as to how to use the different functions (just like the general Linux help command) and gives the syntax and purpose of the functions defined.

>-**allo**

allo allocates a block of memory as required by a user. Displays the base address from which the allocation starts from.

>-**free**

releases the block of allocated memory in the allocate function.

>-**write**

asks for an offset from user and feeds the data provided into the particular offset

>-**display**

reads back data in that particular memory location.

>-**random**

generates upto 5 random numbers from a seed value provided by the user.

>-**verify**

verifies that the previous random pattern with the new set of values from user and if a match occurs, pattern is verified, else displays address of mismatch and values expected and calculated.

>-**exit**

the entire program is in a loop and the exit command can be invoked to terminate the program.

To RUN the code:
>-**Run the "make" command in the code directory**
>-**This automatically generates an executable file by the name of "Project_1" using the predefined Makefile in the folder**
>-**Run the Project_1 executable with "./Project_1" command** 

While making the project we have taken into consideration most of the boundary conditions that could occur during execution, such as performing free or any other memory requiring operation without allocating memory.
Or an invalid user input which will show an invalid flag instead of breaking out of the program.

Basic testing is done via a **stdin** test file with all the functions to be tested along with the required parameters for each function. The compiler automatically feeds the parameters after each function invoked in the stdin file.

The entire project took our team (of 2) about 45 man hours and was a very good learning experience.
