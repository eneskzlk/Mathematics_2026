# Exercise 3 — Noninvertible Matrix

## Question

For

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

## Solution

First check the determinant.

$$
\det A=2\cdot2-4\cdot1=0.
$$

An invertible square matrix must have nonzero determinant, so $A^{-1}$ does not exist. Independently, row 1 is twice row 2. Consequently the rows are linearly dependent, $\mathrm{rank}(A)=1<2$, and the map cannot be inverted.
