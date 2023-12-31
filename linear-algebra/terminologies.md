## Vector Space

Definition: A Vector Space (V; +; ·; R) is non empty set V with two operations:

* $+$ (addition): $V \times V \rightarrow V$
* $.$ (scalar multiplication): $R \times V \rightarrow V$

  which satisfy the following conditions for all u, v and w in V and for all scalars a
and b in R.

1. Additive Closure: u + v ∈ V .
2. Multiplicative Closure: a · u ∈ V .
3. Additive Commutativity: u + v = v + u.
4. Additive Associativity: (u + v) + w = u + (v + w).
5. Existence of a zero vector: There is a special vector $0_{V}$ ∈ V, called the zero vector, such that u + $0_{V}$ = u.
6. Additive Inverse: For every u ∈ V , there is a vector $u^{'}$ called negative (additive inverse) of u such that u + $u^{'}$ = $0_{V}$
7. Unity: 1 · u = u.
8. Associativity of multiplication: (ab) · u = a · (b · u).
9. Distributivity: (a + b) · u = a · u + b · u and a · (u + v) = a · u + a · v.

Assumption:

* S is a Vector Space

Definitions:

* Span (denoted by Span(S)): The set of all linear combinations of the vectors in S
* Spanning Set: Any set $S^{'}$ such that any vector in Span(S) can be written as linear combinations of the vectors in $S^{'}$
* Basis: Linearly Independent subset of S that spans S
* Dimension: Cardinality of Basis


## Matrix

Definition : Rectangular Array of Numbers

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
* Trace of Matrix (denoted by tr(A)) = Sum of elements of the principal diagonal
* Null Space: The Subspace W = { x $\in R^{n} | Ax = 0$ } of $R^{n}$
* Nullity: Dimension of Null Space
* Skey Symmetric Matrix: A = - $A^T$

### Determinant (Only defined for Square Matrices)


* Minor of element $a_{ij}$ (denoted by $M_{ij}$): Determinant of Matrix Obtained by eliminating $i_{th}$ row and $j_{th}$ column
* Cofactor of element $A_{ij}$ (denoted by $C_{ij}$): = $(-1)^{i+j} M_{ij}$ (Signed Minor)

* Determinant of the Matrix A: $\sum\limits_{j = 1}^{j = n}$ $a_{ij} C_{ij}$ for a fixed i

### Equivalence

A is equivalent to B if $B = QAP$ for invertible matrices Q and P. Equivalence of Matrices is an equivalent relation.

* Rank(A) = Rank(B)

### Similarity (Applicable for Square Matrix)

A is similar to B if $B = P^{-1}AP$. Similarity of Matrices is an equivalent relation

* Det(A) = Det(B)

### Linear Transformation

f(x + $\lambda y$) =  $f(x) + \lambda f(y)$

f(a + (-1)(a)) = f(a) - f(a) => f(0) = 0

Assumption:

f: V -> W is a function, T: V -> W is a linear transformation

Definitions:

* Injective Function: f(v1) = f(v2) $\implies v1=v2$
* Surjective Function: for $\forall w \in W$  $\exists v \in V$ such that f(v) = w
* Bijective Function: Function that is both injective and surjective
* Isomorphism: Linear Transformation which is Bijection

Property:

Let $\beta_1$ and $\beta_2$ be 2 ordered basis for V and $\gamma_1$ and $\gamma_2$ be 2 ordered basis for W

Let A be the matrix corresponding to T with respect to $\beta_1$ and $\gamma_1$ and B be the matrix corresponding to T with respect to $\beta_2$ and $\gamma_2$, then A is equivalent to B

B = QAP then

P -> Express the ordered basis $\beta_2$ in terms of $\beta_1$

Q -> Express the ordered basis $\gamma_1$ in terms of $\gamma_2$




Note:

Definitions are simplified in the context of study. 

References:

1. https://mml-book.github.io/book/mml-book.pdf
2. [Linear Algebra](https://drive.google.com/file/d/1jaP-zhFtY6xxnjzt-Tqu38seLamiDHmW/view)



