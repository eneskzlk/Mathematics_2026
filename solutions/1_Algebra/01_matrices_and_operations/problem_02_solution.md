# Exercise 2 — Matrices and Basic Operations

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 \\
-1 & 3 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
4 & -2 \\
0 & 5 \\
\end{pmatrix}
$$

compute

$$
A+B,\qquad A-B,\qquad 3A-2B.
$$

Explain why matrix addition is possible only for matrices of the same size.

## Solution

Addition and subtraction are carried out entry by entry:

$$
A+B=\begin{pmatrix}
5&0 \\
-1&8 \\
\end{pmatrix},\quad
A-B=\begin{pmatrix}
-3&4 \\
-1&-2 \\
\end{pmatrix}.
$$

For the linear combination, first form $3A$ and $2B$:

$$
3A-2B=
\begin{pmatrix}
3-8&6-(-4) \\
-3-0&9-10 \\
\end{pmatrix}
=
\begin{pmatrix}
-5&10 \\
-3&-1 \\
\end{pmatrix}.
$$

Matrices must have equal dimensions for addition: each entry of one needs a corresponding entry in the other. Both matrices here are $2\times2$.
