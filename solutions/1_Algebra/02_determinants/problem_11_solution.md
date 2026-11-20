# Exercise 11 — Determinants

## Question

Compute

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
$$

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

## Solution

Start with

$$
A=\begin{pmatrix}
1&2&3 \\
1&3&4 \\
1&4&6 \\
\end{pmatrix}.
$$

Subtract row 1 from both rows 2 and 3:

$$
\begin{pmatrix}
1&2&3 \\
0&1&1 \\
0&2&3 \\
\end{pmatrix}.
$$

Then apply $R_3\leftarrow R_3-2R_2$:

$$
\begin{pmatrix}
1&2&3 \\
0&1&1 \\
0&0&1 \\
\end{pmatrix}.
$$

All three operations have the form $R_i\leftarrow R_i+kR_j$ and leave the determinant unchanged. The final matrix is triangular, hence

$$
\det A=1\cdot1\cdot1=1.
$$
