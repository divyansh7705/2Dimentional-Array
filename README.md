# 2Dimentional-Array

## AIM:-
To study and implement 2 Dimensional arrays in C++ <br>

## Software Used :-
VS code <br>

## Theory :-
A 2D array is a data structure that with a grid, where each element is identified by two indices: a row index and a column index.<br>
```
int matrix[3][4] = {
    {1, 2, 3, 4},
    {5, 6, 7, 8},
    {9, 10, 11, 12}
};
```
Features of 2D array:<br>

Structure: A 2D array is essentially an array of arrays, where each element of the outer array is another array representing a row in the matrix.<br>
Indexing: Elements in a 2D array are accessed using two indices.<br>
Contiguous Memory: In C++, a 2D array is stored in memory as a continuous block of memory.<br>
Operations: Various operations can be performed on 2D arrays, including addition, subtraction, and multiplication (in the case of matrices).<br>

Uses of 2D Arrays:<br>

Used in applications including computer graphics, image processing.<br>
Used in scientific simulations, spreadsheets.<br>
Used in mathematical representation of matrix.<br>


## Algorithm for Matrix Addition

1. **Input Matrix Dimensions**:
   - Prompt the user to input the number of rows and columns for the first matrix.
   - Prompt the user to input the number of rows and columns for the second matrix.

2. **Check Matrix Dimension Compatibility**:
   - Verify that the number of rows and columns of the first matrix are equal to those of the second matrix. If not, output an error message indicating that matrix addition is not possible.

3. **Input Matrix Elements**:
   - If the matrices are compatible:
     - Prompt the user to enter the elements of the first matrix, row by row.
     - Prompt the user to enter the elements of the second matrix, row by row.

4. **Initialize Resultant Matrix**:
   - Create a matrix to store the result of the addition, with the same dimensions as the input matrices.

5. **Perform Matrix Addition**:
   - Loop through each element of the matrices:
     - For each element at position `(i, j)`, calculate the sum of the corresponding elements from the two matrices.
     - Store the result in the resultant matrix.

6. **Output the Resultant Matrix**:
   - Print the elements of the resultant matrix, row by row.

7. **End the Program**:
   - Conclude the program after displaying the resultant matrix.


## Algorithm for Calculating and Displaying the Sum of Diagonal Elements

1. **Initialize Matrix Dimensions**:
   - Define the size of the matrix `n` (e.g., `n = 3` for a 3x3 matrix).

2. **Initialize Matrix**:
   - Create and initialize a 2D matrix `a` of size `n x n` with predefined values.

3. **Initialize Diagonal Sum**:
   - Create a variable `diagonalSum` and set it to `0`.

4. **Calculate Diagonal Sum**:
   - Loop through each index `i` from `0` to `n-1`:
     - Add the value of the element at position `(i, i)` of the matrix to `diagonalSum`.

5. **Print the Matrix**:
   - Loop through each row index `i` from `0` to `n-1`:
     - Loop through each column index `j` from `0` to `n-1`:
       - Print the element at position `(i, j)` of the matrix.
     - Move to the next line after printing all columns of the current row.

6. **Print the Diagonal Sum**:
   - Output the value of `diagonalSum`.

7. **End the Program**:
   - Conclude the program after displaying the matrix and the diagonal sum.

## Algorithm for Inputting and Displaying a 2x3 Matrix

1. **Initialize Matrix**:
   - Define a 2x3 matrix.

2. **Input Matrix Elements**:
   - Use a loop to iterate through each row of the matrix.
   - For each row, use another loop to iterate through each column.
   - For each element, read the input from the user and store it in the matrix.

3. **Display the Matrix**:
   - Use a loop to iterate through each row of the matrix.
   - For each row, use another loop to iterate through each column.
   - Print each element followed by a space.
   - Move to the next line after printing all elements of the current row.

  ## Algorithm for Matrix Multiplication

1. **Initialize Matrices**:
   - Define matrices `A` and `B` with predefined values.
   - Define a result matrix `C` initialized to zero.

2. **Check Matrix Multiplication Feasibility**:
   - Verify if the number of columns in matrix `A` is equal to the number of rows in matrix `B`.
   - If they are not equal, matrix multiplication is not possible, and an error message is displayed.

3. **Input Matrices**:
   - Read or initialize matrix `A` (of size `r1 x c1`).
   - Read or initialize matrix `B` (of size `r2 x c2`).

4. **Perform Matrix Multiplication**:
   - Loop through each row of matrix `A`.
   - For each row of `A`, loop through each column of matrix `B`.
   - Compute the sum of the products of corresponding elements from the row of `A` and the column of `B`.
   - Store the result in the corresponding position of matrix `C`.

5. **Output Matrices**:
   - Print matrix `A`.
   - Print matrix `B`.
   - Print the resultant matrix `C` after multiplication.

6. **End Program**:
   - Conclude the program after displaying the matrices and the result.


## Algorithm for Matrix Transposition

1. **Initialize Matrices**:
   - Define the dimensions of matrix `A` (e.g., `n` rows and `m` columns).
   - Define matrix `A` with initial values.
   - Define matrix `T` with dimensions `m x n` to store the transposed matrix.

2. **Print Original Matrix**:
   - Loop through each row of matrix `A`.
   - For each row, loop through each column and print the elements.

3. **Compute Transpose**:
   - Loop through each row index `i` of matrix `A`.
   - For each row, loop through each column index `j`:
     - Assign the value of `A[i][j]` to `T[j][i]`.

4. **Print Transposed Matrix**:
   - Loop through each row of matrix `T`.
   - For each row, loop through each column and print the elements.

5. **End the Program**:
   - Conclude the program after displaying both the original and transposed matrices.

## conclusion :- <br>
In this experiment we performed different programs on matrix <br>
