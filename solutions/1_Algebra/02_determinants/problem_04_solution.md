# Exercise 4 — Determinants

## Question

Without expanding the determinant, compute

$$
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
$$

State the rule for an arbitrary triangular matrix and explain it using this example.

## Solution

The matrix is upper triangular; every entry below the main diagonal is zero. A triangular matrix has determinant equal to the product of its diagonal entries. Hence

$$
\det\begin{pmatrix}
2&4&1 \\
0&-3&5 \\
0&0&7 \\
\end{pmatrix}
=2(-3)(7)=-42.
$$

This rule works for upper and lower triangular matrices of any square size because the other terms in the determinant expansion contain a zero below or above the diagonal.
