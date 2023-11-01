Matrix: Rectangular Array of Numbers

Assumptions:

* A is a matrix with m rows and n columns (wherever we take $a_{ij}$, 1 < i <= m and 1 <= j < n)
* Determinant of a 1 by 1 matrix [x] = x

Definitions:

* Element: An individual value. $a_{mn}$ => value at $m_{th}$ row and $n_{th}$ column.
* Dimension: m by n
* Row Matrix: m = 1 (1 by n matrix)
* Column Matrix: n = 1 (m by 1 matrix)
* Square Matrix: m = n (n by n matrix)
* Diagonal Matrix: m = n and $a_{ij} = 0 \space\forall$ (i,j) where i != j (All elements except diagonal elements are 0)
* Scalar Matrix: Diagonal Matrix with equal diagonal elements
* Rank: No. of linearly independent rows/columns
* Transpose (denoted at $A^t$): $\forall$ (i,j) $A_{ij}$ <-> $A_{ji}$ (<-> denotes swap)

### Determinant (Only defined for Square Matrices)


* Minor of element $a_{ij}$ (denoted by $M_{ij}$): Determinant of Matrix Obtained by eliminating $i_{th}$ row and $j_{th}$ column
* Cofactor of element $A_{ij}$ (denoted by $C_{ij}$): = $(-1)^{i+j} M_{ij}$ (Signed Minor)

* Determinant of the Matrix A: $\sum\limits_{j = 1}^{j = n}$ $a_{ij} C_{ij}$ for a fixed i


Note:

Definitions are simplified in the context of study. 



