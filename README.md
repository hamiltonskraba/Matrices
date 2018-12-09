# Matrices
This Bash script explores the basic functionality of a Unix environment by calculating basic matrix operations from either a file
or stdin. The following functions are available:

matrix dims [MATRIX]
matrix transpose [MATRIX]
matrix mean [MATRIX]
matrix add MATRIX_LEFT MATRIX_RIGHT
matrix multiply MATRIX_LEFT MATRIX_RIGHT

dims will print the dimensions of the matrix as the number of rows, followed by a space, then the number of columns.
transpose will reflect the elements of the matrix along the main diagonal
mean will take an MxN matrix and return an 1xN row vector, where the first element is the mean of column one, the second element is the mean of column two, and so on.
add will take two MxN matrices and add them together element-wise to produce an MxN matrix
multiply will take an MxN and NxP matrix and produce an MxP matrix. 

