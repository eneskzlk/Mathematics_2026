# Exercise 4 — Matrices and Basic Operations

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
3 & 1 \\
\end{pmatrix}
$$

compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

## Solution

A product entry is the dot product of a row of the first matrix with a column of the second:

$$
AB=\begin{pmatrix}
1(2)+2(3)&1(0)+2(1) \\
0(2)+1(3)&0(0)+1(1) \\
\end{pmatrix}
=\begin{pmatrix}
8&2 \\
3&1 \\
\end{pmatrix}.
$$

Reversing the order gives

$$
BA=\begin{pmatrix}
2(1)+0(0)&2(2)+0(1) \\
3(1)+1(0)&3(2)+1(1) \\
\end{pmatrix}
=\begin{pmatrix}
2&4 \\
3&7 \\
\end{pmatrix}.
$$

Since the entries differ, $AB\ne BA$. Matrix multiplication is not commutative in general.
