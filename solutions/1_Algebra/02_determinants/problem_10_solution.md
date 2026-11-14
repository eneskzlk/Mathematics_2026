# Exercise 10 — Determinants

The second row is twice the first:

$$
(2,4,6)=2(1,2,3).
$$

Two proportional rows are linearly dependent. Consequently the matrix has determinant zero:

$$
\det\begin{pmatrix}
1&2&3 \\
2&4&6 \\
0&1&5 \\
\end{pmatrix}=0.
$$

As a check, the row operation $R_2\leftarrow R_2-2R_1$ produces an entire row of zeros without changing the determinant. A matrix with a zero row cannot be invertible.
