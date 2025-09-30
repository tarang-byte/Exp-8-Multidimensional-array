Aim:
Accepts a matrix of size r × c from the user.

1.Displays the original matrix.
2.Computes and stores the transpose of the matrix.
3.Addition of matrix.
4.Multiplication of matrix.
5.Addition of only diagoal element.

Theory:
Two  for loop  is required to Display the matrix, and asking the 
user to provide the value of rows and columns respectively,
i is for rows and j is for columns.
For transpose of matrix , new matrix will be like rows will become 
columns and vice-versa.
For Addition of matrix using ' + ' arithmetic operation and for 
multiplication '*'.
For Addition of diagonal elements check the condition if
i==j or not if it's equal , then store the sum in another 
sum variable.

 
Conclusion;
Initialisation of multidimensional array ,and how to display it,
and performed various operations on matrix, Learned about the 
concept of nested for loop, index position of array value.


| **Variable**  | **Description**                                           | **Operation**            |
| ------------- | --------------------------------------------------------- | ------------------------ |
| `ar[i][j]`     | Element at row `i` and column `j` of matrix A             | Used in all operations   |
| `br[i][j]`     | Element at row `i` and column `j` of matrix B             | Addition, Multiplication |
| `C[i][j]`     | Resultant element after performing the operation          | Addition, Multiplication |
| `tr[j][i]`    | Element at row `j`, column `i` of transposed matrix A     | Transpose                |
| `sum` | Variable storing the sum of diagonal elements of a matrix | Diagonal sum             |
| `i`           | Row index in loops                                        | All operations           |
| `j`           | Column index in loops                                     | All operations           |
| `k`           | Intermediate index used for multiplication summation      | Multiplication           |
