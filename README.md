# C-Matrix-Multiplication
Matrix-Multiplication
This program calculates the product of two matrices. It reads the size and values of the input matrices from the command line. The elements of the given matrices and the product matrix fit into the int data type. All input values are assumed to be valid.

## Compilation and Execution
Clone the repository: git clone https://github.com/therealvoric/C-Matrix-Multiplication.git
Compile the code: gcc matrixmul.c -o matrixmul
Run the program: ./matrixmul
## Usage
The program prompts for the size of the two input matrices.
Enter the values for the elements of the input matrices when prompted.
The program calculates the product of the two matrices.
The result, i.e., the product matrix, is displayed on the console.
## Functions
The program consists of the following functions:

read_array_elements(int n, int a[][n]): Reads the elements of a matrix with size n x n from the command line.
print_2d_array(int n, int a[][n]): Prints a 2D array with size n x n on the console.
multiply_arrays(int n, int p, int m1[][n], int m2[][p], int res[][p]): Calculates the product of two matrices and stores the result in a new matrix.
## Example
``` 
Enter the size of the first matrix: 2
Enter the elements of the first matrix:
1 2
3 4

Enter the size of the second matrix: 2
Enter the elements of the second matrix:
5 6
7 8

The product of the matrices is:
19 22
43 50

``` 
## Contribution
Contributions to this project are welcome. Feel free to submit a pull request.
