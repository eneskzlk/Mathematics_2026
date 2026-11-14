# Exercise 13 — Determinants

For the matrix

$$
A=\begin{pmatrix}
1&2&3\\
2&5&7\\
1&0&2\\
\end{pmatrix},
$$

apply $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1&2&3\\
0&1&1\\
0&-2&-1\\
\end{pmatrix}.
$$

Next apply $R_3\leftarrow R_3+2R_2$:

$$
\begin{pmatrix}
1&2&3\\
0&1&1\\
0&0&1\\
\end{pmatrix}.
$$

Every step adds a multiple of one row to another and preserves the determinant. Taking the diagonal product yields $\det A=1$.
