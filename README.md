# EECS348-Lab06: IDE, compiled programs (C++ programming), Git

** Problem Description

You are tasked with implementing a C++ program that performs various operations on square matrices using functions and arrays (no classes or objects yet). Your program should read matrix data from a file, perform matrix operations, and output the results. The max size of the square matrices should be defined as a static constant 100 but the actual size of the square matrix will be the first line of data, and it will less than or equal to 100. For this assignment, you will write the following functions:

1. Read values from a file into a matrix:

Create a function to read matrix data from a specified file and store it in a 2D array.

2. Print a matrix:

Implement a function to display a matrix in a user-friendly format. The matrix values should nicely align in a column.

3. Add two matrices and place the result in a third matrix; print the result:

Create a function that adds two matrices of the same size and stores the result in a third matrix. Display the resulting matrix.

4. Multiply two matrices and place the result in a third matrix; print the result:

Implement a function for matrix multiplication (matrix1 * matrix2 = result_matrix). Display the resulting matrix.

5. Subtract the second matrix from the first matrix and place the result in a third matrix; print the result:

Develop a function to subtract one matrix from another and store the result in a third matrix. Display the resulting matrix.

** Constraints

The matrices are square matrices (NxN), where N is defined as a static constant. The input matrices are read from a file named "matrix_input.txt". The output matrices are displayed on the console.

Place only the functional prototypes before the main function. Place the function bodies below the main program.
