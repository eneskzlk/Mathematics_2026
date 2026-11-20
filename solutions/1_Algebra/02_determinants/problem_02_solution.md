# Exercise 2 — Determinants

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
$$

compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

## Solution

For the matrix

$$
A=\begin{pmatrix}
1&2&-1 \\
0&3&4 \\
2&1&5 \\
\end{pmatrix},
$$

Sarrus' rule sums the three forward diagonal products and subtracts the three backward products:

$$
\det A=(1\cdot3\cdot5+2\cdot4\cdot2+(-1)\cdot0\cdot1)
-((-1)\cdot3\cdot2+1\cdot4\cdot1+2\cdot0\cdot5)
=31-(-2)=33.
$$

To check the result, apply $R_3\leftarrow R_3-2R_1$. Adding a multiple of one row to another preserves the determinant. The third row becomes $(0,-3,7)$, so expansion along the first column has only one nonzero term.

$$
\det A=1\bigl(3\cdot7-4(-3)\bigr)=33.
$$
