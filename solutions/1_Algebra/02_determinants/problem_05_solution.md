# Exercise 5 — Determinants

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

## Solution

Use row replacements, which do not change the determinant. Beginning with

$$
A=\begin{pmatrix}
1&2&3 \\
2&1&0 \\
-1&4&2 \\
\end{pmatrix},
$$

apply $R_2\leftarrow R_2-2R_1$, which preserves the determinant and changes row 2 to $(0,-3,-6)$. Then apply $R_3\leftarrow R_3+R_1$, which also preserves the determinant and changes row 3 to $(0,6,5)$.

$$
\begin{pmatrix}
1&2&3 \\
0&-3&-6 \\
0&6&5 \\
\end{pmatrix}.
$$

Expansion along the first column gives

$$
\det A=1((-3)(5)-(-6)(6))=-15+36=21.
$$

Neither row replacement changed the determinant. The result is also verified by direct first-row expansion of the original matrix: $2-8+27=21$.
