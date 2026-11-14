# Exercise 8 — Matrices and Basic Operations

Start with

$$
A=\begin{pmatrix}
1&2&-1 \\
2&4&1 \\
-1&1&3 \\
\end{pmatrix}.
$$

First, $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1&2&-1 \\
0&0&3 \\
-1&1&3 \\
\end{pmatrix}.
$$

Next, $R_3\leftarrow R_3+R_1$:

$$
\begin{pmatrix}
1&2&-1 \\
0&0&3 \\
0&3&2 \\
\end{pmatrix}.
$$

Finally swap $R_2$ and $R_3$:

$$
\begin{pmatrix}
1&2&-1 \\
0&3&2 \\
0&0&3 \\
\end{pmatrix}.
$$

To undo all operations, reverse their order: swap rows 2 and 3 again, subtract row 1 from row 3, and then add twice row 1 to row 2. Each operation is reversible.
